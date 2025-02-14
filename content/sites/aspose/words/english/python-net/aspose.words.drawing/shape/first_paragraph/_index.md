﻿---
title: first_paragraph property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets the first paragraph in the shape."
type: docs
weight: 60
url: /python-net/aspose.words.drawing/shape/first_paragraph/
---

## Shape.first_paragraph property

Gets the first paragraph in the shape.


### Examples

Shows how to create and format a text box.

```python
doc = aw.Document()

# Create a floating text box.
text_box = aw.drawing.Shape(doc, aw.drawing.ShapeType.TEXT_BOX)
text_box.wrap_type = aw.drawing.WrapType.NONE
text_box.height = 50
text_box.width = 200

# Set the horizontal, and vertical alignment of the text inside the shape.
text_box.horizontal_alignment = aw.drawing.HorizontalAlignment.CENTER
text_box.vertical_alignment = aw.drawing.VerticalAlignment.TOP

# Add a paragraph to the text box and add a run of text that the text box will display.
text_box.append_child(aw.Paragraph(doc))
para = text_box.first_paragraph
para.paragraph_format.alignment = aw.ParagraphAlignment.CENTER
run = aw.Run(doc)
run.text = "Hello world!"
para.append_child(run)

doc.first_section.body.first_paragraph.append_child(text_box)

doc.save(ARTIFACTS_DIR + "Shape.create_text_box.docx")
```

### See Also

* module [aspose.words.drawing](../../)
* class [Shape](../)

