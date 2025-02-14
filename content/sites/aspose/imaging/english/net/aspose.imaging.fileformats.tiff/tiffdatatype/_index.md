---
title: TiffDataType
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7860
url: /net/aspose.imaging.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

The tiff data type.

```csharp
public abstract class TiffDataType : IComparable
```

## Properties

| Name | Description |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| abstract [Count](../../aspose.imaging.fileformats.tiff/tiffdatatype/count) { get; } | Gets the count of elements. |
| abstract [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Gets tag id integer representation. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Gets the tag id. |
| abstract [TagType](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagtype) { get; } | Gets the tag type. |
| abstract [Value](../../aspose.imaging.fileformats.tiff/tiffdatatype/value) { get; set; } | Gets or sets the value this data type contains. |

## Methods

| Name | Description |
| --- | --- |
| static [ReadTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/readtag)(TiffStreamReader, long) | Reads the tag data. |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Performs a deep clone of this instance. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Returns a String that represents this instance. |
| abstract [WriteAdditionalData](../../aspose.imaging.fileformats.tiff/tiffdatatype/writeadditionaldata)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
