---
title: PsdLoadOptions
second_title: Aspose.PSD for .NET API 参考
description: Psd 加载选项
type: docs
weight: 4700
url: /zh/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd 加载选项

```csharp
public class PsdLoadOptions : LoadOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PsdLoadOptions](psdloadoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor) { get; set; } | 获取或设置[`Image`](../../aspose.psd/image)背景[`Color`](../../aspose.psd/color) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode) { get; set; } | 获取或设置数据恢复模式 |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel) { get; set; } | 获取或设置一个值，指示是否[忽略 alpha 通道]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate) { get; set; } | 获取或设置一个值，该值指示在 UpdateText 操作执行时是否会忽略 PSD 文本层固定宽度。 |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource) { get; set; } | 获取或设置一个值，该值指示是否[加载影响资源]（默认不加载资源）。设置此选项时，仅支持的效果将呈现为最终合并图像。 |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode) { get; set; } | 获取或设置一个值，指示是否[使用只读模式]。这是只读模式，支持与 Adobe Photoshop 相同的兼容性。 设置此选项后，应用于图层的所有更改都不会保存到最终图像。所有数据均来自 ImageData 部分，因此它与 Photoshop 相同。 默认情况下，所有加载的图像都与 Adobe Photoshop 兼容。 |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource) { get; set; } | 获取或设置一个值，表示是否[使用磁盘加载特效资源]（默认使用磁盘加载特效资源，但如果足够的话可以通过设置此值来使用内存）。 |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion) { get; set; } | 获取或设置一个值，该值指示是否应应用 ICC 配置文件转换。 |

### 例子

以下示例演示了文档转换进度正常且无异常。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### 也可以看看

* class [LoadOptions](../../aspose.psd/loadoptions)
* 命名空间 [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
