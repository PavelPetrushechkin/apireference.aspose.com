﻿---
title: lines_per_page property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the number of lines per page in the document grid."
type: docs
weight: 250
url: /python-net/aspose.words/pagesetup/lines_per_page/
---

## PageSetup.lines_per_page property

Gets or sets the number of lines per page in the document grid.

Minimum value of the property is 1. Maximum value depends on page height and font size of the Normal
style. Minimum line pitch is 136 percent of the font size. For example, maximum number of lines per page of
a Letter page with one-inch margins is 39.

By default, the property has a value, on which line pitch is in 1.5 times greater than font size of
the Normal style.




### Examples

Shows how to specify a limit for the number of lines that each page may have.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Enable pitching, and then use it to set the number of lines per page in this section.
# A large enough font size will push some lines down onto the next page to avoid overlapping characters.
builder.page_setup.layout_mode = aw.SectionLayoutMode.LINE_GRID
builder.page_setup.lines_per_page = 15

builder.paragraph_format.snap_to_grid = True

for i in range(30):
    builder.write("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ")

doc.save(ARTIFACTS_DIR + "PageSetup.lines_per_page.docx")
```

### See Also

* module [aspose.words](../../)
* class [PageSetup](../)

