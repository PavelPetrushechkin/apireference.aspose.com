﻿---
title: shading property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns a Shading object that refers to the shading formatting for the paragraph."
type: docs
weight: 270
url: /python-net/aspose.words/paragraphformat/shading/
---

## ParagraphFormat.shading property

Returns a Shading object that refers to the shading formatting for the paragraph.


### Examples

Shows how to decorate text with borders and shading.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

borders = builder.paragraph_format.borders
borders.distance_from_text = 20
borders.left.line_style = aw.LineStyle.DOUBLE
borders.right.line_style = aw.LineStyle.DOUBLE
borders.top.line_style = aw.LineStyle.DOUBLE
borders.bottom.line_style = aw.LineStyle.DOUBLE

shading = builder.paragraph_format.shading
shading.texture = aw.TextureIndex.TEXTURE_DIAGONAL_CROSS
shading.background_pattern_color = drawing.Color.light_coral
shading.foreground_pattern_color = drawing.Color.light_salmon

builder.write("This paragraph is formatted with a double border and shading.")
doc.save(ARTIFACTS_DIR + "DocumentBuilder.apply_borders_and_shading.docx")
```

### See Also

* module [aspose.words](../../)
* class [ParagraphFormat](../)

