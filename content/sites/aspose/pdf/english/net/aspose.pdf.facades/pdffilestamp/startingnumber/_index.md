---
title: StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100 document pages will have numbers 100 101 102...
type: docs
weight: 100
url: /net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

### Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../../pdffilestamp)
* namespace [Aspose.Pdf.Facades](../../pdffilestamp)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
