---
title: GetLayersByLinkGroupId
second_title: Aspose.PSD for .NET API 参考
description: 通过链接组 id 获取图层
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

通过链接组 id 获取图层。

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| linkGroupId | Int16 | 链接组 ID。 |

### 返回值

层数组。

### 例子

以下示例演示了如何在 Aspose.PSD 中操作链接层

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 链接一个链接组中的所有层
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 获取一层的id
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // 通过链接组 id 获取所有链接层。
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 从组中取消链接每一层
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // 为组中没有层的链接组 ID 检索 NULL。
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 也可以看看

* class [Layer](../../layer)
* class [LinkedLayersManager](../../linkedlayersmanager)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
