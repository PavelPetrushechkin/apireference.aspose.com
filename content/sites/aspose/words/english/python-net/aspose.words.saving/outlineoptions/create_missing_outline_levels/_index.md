﻿---
title: create_missing_outline_levels property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets a value determining whether or not to create missing outline levels when the document is  exported."
type: docs
weight: 30
url: /python-net/aspose.words.saving/outlineoptions/create_missing_outline_levels/
---

## OutlineOptions.create_missing_outline_levels property

Gets or sets a value determining whether or not to create missing outline levels when the document is 
exported.

Default value for this property is **false**.




### Examples

Shows how to work with outline levels that do not contain any corresponding headings when saving a PDF document.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert headings that can serve as TOC entries of levels 1 and 5.
builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING1

self.assertTrue(builder.paragraph_format.is_heading)

builder.writeln("Heading 1")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING5

builder.writeln("Heading 1.1.1.1.1")
builder.writeln("Heading 1.1.1.1.2")

# Create a "PdfSaveOptions" object that we can pass to the document's "save" method
# to modify how that method converts the document to .PDF.
save_options = aw.saving.PdfSaveOptions()

# The output PDF document will contain an outline, which is a table of contents that lists headings in the document body.
# Clicking on an entry in this outline will take us to the location of its respective heading.
# Set the "headings_outline_levels" property to "5" to include all headings of levels 5 and below in the outline.
save_options.outline_options.headings_outline_levels = 5

# This document contains headings of levels 1 and 5, and no headings with levels of 2, 3, and 4.
# The output PDF document will treat outline levels 2, 3, and 4 as "missing".
# Set the "create_missing_outline_levels" property to "True" to include all missing levels in the outline,
# leaving blank outline entries since there are no usable headings.
# Set the "create_missing_outline_levels" property to "False" to ignore missing outline levels,
# and treat the outline level 5 headings as level 2.
save_options.outline_options.create_missing_outline_levels = create_missing_outline_levels

doc.save(ARTIFACTS_DIR + "PdfSaveOptions.create_missing_outline_levels.pdf", save_options)
```

### See Also

* module [aspose.words.saving](../../)
* class [OutlineOptions](../)

