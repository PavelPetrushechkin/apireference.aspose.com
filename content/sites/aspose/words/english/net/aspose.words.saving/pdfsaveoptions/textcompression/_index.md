---
title: TextCompression
second_title: Aspose.Words for .NET API Reference
description: Specifies compression type to be used for all textual content in the document.
type: docs
weight: 270
url: /net/aspose.words.saving/pdfsaveoptions/textcompression/
---
## PdfSaveOptions.TextCompression property

Specifies compression type to be used for all textual content in the document.

```csharp
public PdfTextCompression TextCompression { get; set; }
```

## Remarks

Default is Flate.

Significantly increases output size when saving a document without compression.

## Examples

Shows how to apply text compression when saving a document to PDF.

```csharp
Document doc = new Document();
DocumentBuilder builder = new DocumentBuilder(doc);

for (int i = 0; i < 100; i++)
    builder.Writeln("Lorem ipsum dolor sit amet, consectetur adipiscing elit, " +
                    "sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.");

// Create a "PdfSaveOptions" object that we can pass to the document's "Save" method
// to modify how that method converts the document to .PDF.
PdfSaveOptions options = new PdfSaveOptions();

// Set the "TextCompression" property to "PdfTextCompression.None" to not apply any
// compression to text when we save the document to PDF.
// Set the "TextCompression" property to "PdfTextCompression.Flate" to apply ZIP compression
// to text when we save the document to PDF. The larger the document, the bigger the impact that this will have.
options.TextCompression = pdfTextCompression;

doc.Save(ArtifactsDir + "PdfSaveOptions.TextCompression.pdf", options);
```

### See Also

* enum [PdfTextCompression](../../pdftextcompression)
* class [PdfSaveOptions](../../pdfsaveoptions)
* namespace [Aspose.Words.Saving](../../pdfsaveoptions)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
