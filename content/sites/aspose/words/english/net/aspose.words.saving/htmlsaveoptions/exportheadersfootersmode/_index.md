---
title: ExportHeadersFootersMode
second_title: Aspose.Words for .NET API Reference
description: Specifies how headers and footers are output to HTML MHTML or EPUB. Default value is PerSection for HTML/MHTML and None for EPUB.
type: docs
weight: 170
url: /net/aspose.words.saving/htmlsaveoptions/exportheadersfootersmode/
---
## HtmlSaveOptions.ExportHeadersFootersMode property

Specifies how headers and footers are output to HTML, MHTML or EPUB. Default value is PerSection for HTML/MHTML and None for EPUB.

```csharp
public ExportHeadersFootersMode ExportHeadersFootersMode { get; set; }
```

## Remarks

It is hard to meaningfully output headers and footers to HTML because HTML is not paginated.

When this property is PerSection, Aspose.Words exports only primary headers and footers at the beginning and the end of each section.

When it is FirstSectionHeaderLastSectionFooter only first primary header and the last primary footer (including linked to previous) are exported.

You can disable export of headers and footers altogether by setting this property to None.

## Examples

Shows how to omit headers/footers when saving a document to HTML.

```csharp
Document doc = new Document(MyDir + "Header and footer types.docx");

// This document contains headers and footers. We can access them via the "HeadersFooters" collection.
Assert.AreEqual("First header", doc.FirstSection.HeadersFooters[HeaderFooterType.HeaderFirst].GetText().Trim());

// Formats such as .html do not split the document into pages, so headers/footers will not function the same way
// they would when we open the document as a .docx using Microsoft Word.
// If we convert a document with headers/footers to html, the conversion will assimilate the headers/footers into body text.
// We can use a SaveOptions object to omit headers/footers while converting to html.
HtmlSaveOptions saveOptions =
    new HtmlSaveOptions(SaveFormat.Html) { ExportHeadersFootersMode = ExportHeadersFootersMode.None };

doc.Save(ArtifactsDir + "HeaderFooter.ExportMode.html", saveOptions);

// Open our saved document and verify that it does not contain the header's text
doc = new Document(ArtifactsDir + "HeaderFooter.ExportMode.html");

Assert.IsFalse(doc.Range.Text.Contains("First header"));
```

### See Also

* enum [ExportHeadersFootersMode](../../exportheadersfootersmode)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [Aspose.Words.Saving](../../htmlsaveoptions)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
