---
title: ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Sets the mode for extract texts result.
type: docs
weight: 40
url: /net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Sets the mode for extract text's result.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 is pure text mode and 1 is raw ordering mode. Default is 0.

### Examples

The example demonstratres the `ExtractTextMode` property usage in text extraction scenario.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### See Also

* class [PdfExtractor](../../pdfextractor)
* namespace [Aspose.Pdf.Facades](../../pdfextractor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
