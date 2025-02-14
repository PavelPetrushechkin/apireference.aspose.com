---
title: GaussianBlurSmartFilter
second_title: Aspose.PSD for .NET API 参考
description: GaussianBlur 智能滤镜
type: docs
weight: 3370
url: /zh/net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
## GaussianBlurSmartFilter class

GaussianBlur 智能滤镜。

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter)() | 初始化[`GaussianBlurSmartFilter`](../gaussianblursmartfilter)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode) { get; set; } | 获取或设置混合模式。 |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid) { get; } | 获取智能过滤器类型标识符。 |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled) { get; set; } | 获取或设置智能过滤器的启用状态。 |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name) { get; } | 获取智能过滤器名称。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity) { get; set; } | 获取或设置智能滤镜的不透明度值。 |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius) { get; set; } | 获取或设置高斯智能滤波器的半径。 |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor) { get; } | 带有智能过滤器数据的源描述符结构。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply)(RasterImage) | 将当前过滤器应用于输入[`RasterImage`](../../aspose.psd/rasterimage)图像. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask)(Layer) | 将当前过滤器应用于输入[`Layer`](../../aspose.psd.fileformats.psd.layers/layer)掩码数据. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone)() | 生成当前类型实例的成员克隆。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype) | 当前智能过滤器的标识符。 |

### 例子

这个例子演示了智能过滤器接口的支持。

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // 编辑智能过滤器
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // 检查过滤器值
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // 更新过滤器值
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // 添加新的过滤器项
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // 应用更改
    smartObj.SmartFilters.UpdateResourceValues();

    // 应用过滤器
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // 检查过滤器值
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### 也可以看看

* class [SmartFilter](../smartfilter)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
