---
title: SerializeExifData
second_title: Aspose.PSD for .NET API 参考
description: 序列化 EXIF 数据写入标签值和内容影响最大的尺寸标签是缩略图标签内容
type: docs
weight: 270
url: /zh/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
## JpegExifData.SerializeExifData method

序列化 EXIF 数据。写入标签值和内容。影响最大的尺寸标签是缩略图标签内容。

```csharp
public byte[] SerializeExifData()
```

### 返回值

序列化的 EXIF 数据。

### 评论

整体段大小必须小于或等于 MaxExifSegmentSize 字节才能生成正确的 jpeg 图像。 提示：尝试减小缩略图大小或更改其压缩，以防 EXIF 段大小过大。

### 也可以看看

* class [JpegExifData](../../jpegexifdata)
* 命名空间 [Aspose.PSD.Exif](../../jpegexifdata)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
