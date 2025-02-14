﻿---
title: fill property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets fill formatting for the shape."
type: docs
weight: 170
url: /python-net/aspose.words.drawing/shapebase/fill/
---

## ShapeBase.fill property

Gets fill formatting for the shape.


### Examples

Shows how to fill a shape with a solid color.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Write some text, and then cover it with a floating shape.
builder.font.size = 32
builder.writeln("Hello world!")

shape = builder.insert_shape(aw.drawing.ShapeType.CLOUD_CALLOUT, aw.drawing.RelativeHorizontalPosition.LEFT_MARGIN, 25,
    aw.drawing.RelativeVerticalPosition.TOP_MARGIN, 25, 250, 150, aw.drawing.WrapType.NONE)

# Use the "stroke_color" property to set the color of the outline of the shape.
shape.stroke_color = drawing.Color.cadet_blue

# Use the "fill_color" property to set the color of the inside area of the shape.
shape.fill_color = drawing.Color.light_blue

# The "opacity" property determines how transparent the color is on a 0-1 scale,
# with 1 being fully opaque, and 0 being invisible.
# The shape fill by default is fully opaque, so we cannot see the text that this shape is on top of.
self.assertEqual(1.0, shape.fill.opacity)

# Set the shape fill color's opacity to a lower value so that we can see the text underneath it.
shape.fill.opacity = 0.3

doc.save(ARTIFACTS_DIR + "Shape.fill.docx")
```

### See Also

* module [aspose.words.drawing](../../)
* class [ShapeBase](../)

