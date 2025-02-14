---
title: TiffSByteType
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 8000
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/
---
## TiffSByteType class

The tiff signed byte type.

```csharp
public sealed class TiffSByteType : TiffCommonArrayType
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffSByteType](tiffsbytetype)(TiffTags) | Initializes a new instance of the [`TiffSByteType`](../tiffsbytetype) class. |
| [TiffSByteType](tiffsbytetype)(ushort) | Initializes a new instance of the [`TiffSByteType`](../tiffsbytetype) class. |

## Properties

| Name | Description |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count) { get; } | Gets the count of elements. |
| [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/datasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/elementsize) { get; } | Gets the element size in bytes. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Gets tag id integer representation. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Gets the tag id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/tagtype) { get; } | Gets the tag type. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/value) { get; set; } | Gets or sets the value this data type contains. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/values) { get; set; } | Gets or sets the values. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/valuescontainer) { get; } | Gets the values container. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Performs a deep clone of this instance. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Returns a String that represents this instance. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/writeadditionaldata)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* class [TiffCommonArrayType](../tiffcommonarraytype)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
