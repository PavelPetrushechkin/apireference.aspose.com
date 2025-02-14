﻿---
title: epub_navigation_map_level property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the maximum level of headings populated to the navigation map when exporting to IDPF EPUB format"
type: docs
weight: 110
url: /python-net/aspose.words.saving/htmlsaveoptions/epub_navigation_map_level/
---

## HtmlSaveOptions.epub_navigation_map_level property

Specifies the maximum level of headings populated to the navigation map when exporting to IDPF EPUB format.
Default value is ``3``.


Navigation map in IDPF EPUB format allows user agents to provide easy way of navigation 
through the document structure. Usually navigation points correspond to headings in the document. 
To populate headings up to level **N** assign this value to [HtmlSaveOptions.epub_navigation_map_level](./).

By default, three levels of headings are populated: paragraphs of styles **Heading 1**, **Heading 2**
and **Heading 3**.
You can set this property to a value from 1 to 9 to request corresponding maximum level. 
Setting it to zero will reduce navigation map to only document root or roots of document parts.




### Examples

Shows how to filter headings that appear in the navigation panel of a saved Epub document.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Every paragraph that we format using a "Heading" style can serve as a heading.
# Each heading may also have a heading level, determined by the number of its heading style.
# The headings below are of levels 1-3.
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 1")
builder.writeln("Heading #1")
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 2")
builder.writeln("Heading #2")
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 3")
builder.writeln("Heading #3")
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 1")
builder.writeln("Heading #4")
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 2")
builder.writeln("Heading #5")
builder.paragraph_format.style = builder.document.styles.get_by_name("Heading 3")
builder.writeln("Heading #6")

# Epub readers typically create a table of contents for their documents.
# Each paragraph with a "Heading" style in the document will create an entry in this table of contents.
# We can use the "epub_navigation_map_level" property to set a maximum heading level.
# The Epub reader will not add headings with a level above the one we specify to the contents table.
options = aw.saving.HtmlSaveOptions(aw.SaveFormat.EPUB)
options.epub_navigation_map_level = 2

# Our document has six headings, two of which are above level 2.
# The table of contents for this document will have four entries.
doc.save(ARTIFACTS_DIR + "HtmlSaveOptions.epub_headings.epub", options)
```

### See Also

* module [aspose.words.saving](../../)
* class [HtmlSaveOptions](../)

