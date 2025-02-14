---
title: XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Represents options for loading/importing XML file into pdf document.
type: docs
weight: 7400
url: /net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

Represents options for loading/importing XML file into pdf document.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions#constructor)() | Creates [`XmlLoadOptions`](../xmlloadoptions) object without xsl data. |
| [XmlLoadOptions](xmlloadoptions#constructor_1)(Stream) | Creates [`XmlLoadOptions`](../xmlloadoptions) object with xsl data. |
| [XmlLoadOptions](xmlloadoptions#constructor_2)(string) | Creates [`XmlLoadOptions`](../xmlloadoptions) object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Represents file format which [`LoadOptions`](../loadoptions) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream) { get; } | Gets xsl data for converting xml into pdf document. |

### See Also

* class [LoadOptions](../loadoptions)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
