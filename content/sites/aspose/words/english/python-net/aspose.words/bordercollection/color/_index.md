﻿---
title: color property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the border color."
type: docs
weight: 30
url: /python-net/aspose.words/bordercollection/color/
---

## BorderCollection.color property

Gets or sets the border color.

Returns the color of the first border in the collection.

Sets the color of all borders in the collection excluding diagonal borders.




### Examples

Shows how to create green wavy page border with a shadow.

```python
doc = aw.Document()
page_setup = doc.sections[0].page_setup

page_setup.borders.line_style = aw.LineStyle.DOUBLE_WAVE
page_setup.borders.line_width = 2
page_setup.borders.color = drawing.Color.green
page_setup.borders.distance_from_text = 24
page_setup.borders.shadow = True

doc.save(ARTIFACTS_DIR + "PageSetup.page_borders.docx")
```

### See Also

* module [aspose.words](../../)
* class [BorderCollection](../)

