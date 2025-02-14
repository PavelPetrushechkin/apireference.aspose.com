---
title: XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Represents options for loading/importing XSL-FO file into pdf document.
type: docs
weight: 7540
url: /net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Represents options for loading/importing XSL-FO file into pdf document.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions#constructor)() | Creates [`XslFoLoadOptions`](../xslfoloadoptions) object without xsl data. |
| [XslFoLoadOptions](xslfoloadoptions#constructor_1)(Stream) | Creates [`XslFoLoadOptions`](../xslfoloadoptions) object with xsl data. |
| [XslFoLoadOptions](xslfoloadoptions#constructor_2)(string) | Creates [`XslFoLoadOptions`](../xslfoloadoptions) object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath) { get; set; } | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Represents file format which [`LoadOptions`](../loadoptions) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream) { get; } | Gets xsl data for converting xml into pdf document. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist) { get; set; } | XsltArgumentList for inserting values into existing xls parameters  XLS file has 'animal' parameter without value: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); now the converter assumes that there is an 'animal' parameter with the value 'cat' in the XLS file. |

## Fields

| Name | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors |

### See Also

* class [XmlLoadOptions](../xmlloadoptions)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
