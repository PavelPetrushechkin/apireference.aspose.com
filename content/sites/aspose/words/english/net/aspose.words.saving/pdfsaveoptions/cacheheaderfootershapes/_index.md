---
title: CacheHeaderFooterShapes
second_title: Aspose.Words for .NET API Reference
description: Gets or sets a value determining whether or not to cache shapes placed in header and footer of document.
type: docs
weight: 30
url: /net/aspose.words.saving/pdfsaveoptions/cacheheaderfootershapes/
---
## PdfSaveOptions.CacheHeaderFooterShapes property

Gets or sets a value determining whether or not to cache shapes placed in header and footer of document.

```csharp
public bool CacheHeaderFooterShapes { get; set; }
```

## Remarks

Default value is `false` and shapes are not cached.

When the value is `true` shapes graphics are written to the PDF document as an xObject.

Some shapes are not supported for caching(shapes with fields, bookmarks, HRefs).

### See Also

* class [PdfSaveOptions](../../pdfsaveoptions)
* namespace [Aspose.Words.Saving](../../pdfsaveoptions)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
