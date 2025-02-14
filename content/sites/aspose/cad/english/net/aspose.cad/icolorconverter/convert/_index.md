---
title: Convert
second_title: Aspose.CAD for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.cad/icolorconverter/convert/
---
## IColorConverter.Convert method

Converts the passed data to the output format.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | The source format. |
| data | Byte[] | The source data. |
| offset | Int32 | The offset in bytes where data copying should begin. |
| bitStart | Int32 | The bit start. Note this value is not byte aligned value instead this is actual bit where copying should begin. |
| samplesCount | Int32 | The samples count. |
| linesCount | Int32 | The lines count. |
| destFormat | PixelDataFormat | The destination format. |
| outputData | Byte[] | The output data. |
| outputOffset | Int32 | The output offset where data copying should start. |

## Return Value

The converted bytes count.

### See Also

* class [PixelDataFormat](../../pixeldataformat)
* interface [IColorConverter](../../icolorconverter)
* namespace [Aspose.CAD](../../icolorconverter)
* assembly [Aspose.CAD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.CAD.dll -->
