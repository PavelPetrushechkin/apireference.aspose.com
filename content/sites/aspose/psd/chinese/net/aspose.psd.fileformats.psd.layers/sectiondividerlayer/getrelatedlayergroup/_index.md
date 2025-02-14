---
title: GetRelatedLayerGroup
second_title: Aspose.PSD for .NET API 参考
description: 获取LayerGroupaspose.psd.fileformats.psd.layers/layergroup与此有关SectionDividerLayeraspose.psd.fileformats.psd.layers/sectiondividerlayer实例.
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
## SectionDividerLayer.GetRelatedLayerGroup method

获取[`LayerGroup`](../../layergroup)与此有关[`SectionDividerLayer`](../../sectiondividerlayer)实例.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### 返回值

这[`LayerGroup`](../../layergroup)实例。

### 例子

以下代码演示了 SectionDividerLayer 图层以及如何获取与其相关的 LayerGroup。

```csharp
[C#]

// 下面的代码演示了SectionDividerLayer 图层以及如何获取与其相关的LayerGroup。

// 层层级
// [0]: '</图层组>'第 1 组的 SectionDividerLayer
// [1]: 'Layer 1' 常规层
// [2]: '</图层组>'第 2 组的 SectionDividerLayer
// [3]: '</图层组>'第 3 组的 SectionDividerLayer
// [4]: '组 3' GroupLayer
// [5]: '组 2' GroupLayer
// [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // 创建层层次结构
    // 添加 LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 添加常规层
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // 添加 LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // 添加 LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // 获取 SectionDividerLayer 的
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // 使用SectionDividerLayer.GetRelatedLayerGroup()方法，获取相关的LayerGroup实例。
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // 同一个图层组
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // 同一个图层组
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // 同一个图层组

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' 包含 5 层
}
```

### 也可以看看

* class [LayerGroup](../../layergroup)
* class [SectionDividerLayer](../../sectiondividerlayer)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
