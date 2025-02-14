﻿---
title: save_format property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the format in which the document will be saved if this save options object is used"
type: docs
weight: 30
url: /python-net/aspose.words.saving/xpssaveoptions/save_format/
---

## XpsSaveOptions.save_format property

Specifies the format in which the document will be saved if this save options object is used.
Can only be [SaveFormat.XPS](../../../aspose.words/saveformat/#XPS).



### Examples

Shows how to limit the headings' level that will appear in the outline of a saved XPS document.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert headings that can serve as TOC entries of levels 1, 2, and then 3.
builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING1

self.assertTrue(builder.paragraph_format.is_heading)

builder.writeln("Heading 1")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING2

builder.writeln("Heading 1.1")
builder.writeln("Heading 1.2")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING3

builder.writeln("Heading 1.2.1")
builder.writeln("Heading 1.2.2")

# Create an "XpsSaveOptions" object that we can pass to the document's "save" method
# to modify how that method converts the document to .XPS.
save_options = aw.saving.XpsSaveOptions()

self.assertEqual(aw.SaveFormat.XPS, save_options.save_format)

# The output XPS document will contain an outline, a table of contents that lists headings in the document body.
# Clicking on an entry in this outline will take us to the location of its respective heading.
# Set the "headings_outline_levels" property to "2" to exclude all headings whose levels are above 2 from the outline.
# The last two headings we have inserted above will not appear.
save_options.outline_options.headings_outline_levels = 2

doc.save(ARTIFACTS_DIR + "XpsSaveOptions.outline_levels.xps", save_options)
```

### See Also

* module [aspose.words.saving](../../)
* class [XpsSaveOptions](../)

