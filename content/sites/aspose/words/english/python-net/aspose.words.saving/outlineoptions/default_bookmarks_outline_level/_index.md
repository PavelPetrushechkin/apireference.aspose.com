﻿---
title: default_bookmarks_outline_level property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the default level in the document outline at which to display Word bookmarks."
type: docs
weight: 50
url: /python-net/aspose.words.saving/outlineoptions/default_bookmarks_outline_level/
---

## OutlineOptions.default_bookmarks_outline_level property

Specifies the default level in the document outline at which to display Word bookmarks.

Individual bookmarks level could be specified using [OutlineOptions.bookmarks_outline_levels](../bookmarks_outline_levels/) property.

Specify 0 and Word bookmarks will not be displayed in the document outline.
Specify 1 and Word bookmarks will be displayed in the document outline at level 1; 2 for level 2 and so on.

Default is 0. Valid range is 0 to 9.




### Examples

Shows to process bookmarks in headers/footers in a document that we are rendering to PDF.

```python
doc = aw.Document(MY_DIR + "Bookmarks in headers and footers.docx")

# Create a "PdfSaveOptions" object that we can pass to the document's "save" method
# to modify how that method converts the document to .PDF.
save_options = aw.saving.PdfSaveOptions()

# Set the "page_mode" property to "PdfPageMode.USE_OUTLINES" to display the outline navigation pane in the output PDF.
save_options.page_mode = aw.saving.PdfPageMode.USE_OUTLINES

# Set the "default_bookmarks_outline_level" property to "1" to display all
# bookmarks at the first level of the outline in the output PDF.
save_options.outline_options.default_bookmarks_outline_level = 1

# Set the "header_footer_bookmarks_export_mode" property to "HeaderFooterBookmarksExportMode.NONE" to
# not export any bookmarks that are inside headers/footers.
# Set the "header_footer_bookmarks_export_mode" property to "HeaderFooterBookmarksExportMode.FIRST" to
# only export bookmarks in the first section's header/footers.
# Set the "header_footer_bookmarks_export_mode" property to "HeaderFooterBookmarksExportMode.ALL" to
# export bookmarks that are in all headers/footers.
save_options.header_footer_bookmarks_export_mode = header_footer_bookmarks_export_mode

doc.save(ARTIFACTS_DIR + "PdfSaveOptions.header_footer_bookmarks_export_mode.pdf", save_options)
```

### See Also

* module [aspose.words.saving](../../)
* class [OutlineOptions](../)

