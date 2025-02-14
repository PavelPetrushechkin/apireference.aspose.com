﻿---
title: TextBox class
second_title: Aspose.Words for Python via .NET API Reference
description: "Defines attributes that specify how a text is displayed inside a shape."
type: docs
weight: 370
url: /python-net/aspose.words.drawing/textbox/
---

## TextBox class

Defines attributes that specify how a text is displayed inside a shape.


Use the [Shape.text_box](../shape/text_box/) property to access text properties of a shape.
You do not create instances of the [TextBox](./) class directly.




### Properties

| Name | Description |
| --- | --- |
| [fit_shape_to_text](./fit_shape_to_text/) | Determines whether Microsoft Word will grow the shape to fit text. |
| [internal_margin_bottom](./internal_margin_bottom/) | Specifies the inner bottom margin in points for a shape. |
| [internal_margin_left](./internal_margin_left/) | Specifies the inner left margin in points for a shape. |
| [internal_margin_right](./internal_margin_right/) | Specifies the inner right margin in points for a shape. |
| [internal_margin_top](./internal_margin_top/) | Specifies the inner top margin in points for a shape. |
| [layout_flow](./layout_flow/) | Determines the flow of the text layout in a shape. |
| [next](./next/) | Returns or sets a TextBox that represents the next TextBox in a sequence of shapes. |
| [parent](./parent/) | Gets a parent shape for the TextBox. |
| [previous](./previous/) | Returns a TextBox that represents the previous TextBox in a sequence of shapes. |
| [text_box_wrap_mode](./text_box_wrap_mode/) | Determines how text wraps inside a shape. |
| [vertical_anchor](./vertical_anchor/) | Specifies the vertical alignment of the text within a shape. |

### Methods

| Name | Description |
| --- | --- |
|[ break_forward_link()](./break_forward_link/#default) | Breaks the link to the next TextBox. |
|[ is_valid_link_target(target)](./is_valid_link_target/#textbox) | Determines whether this TextBox can be linked to the target Textbox. |

### Examples

Shows how to set the orientation of text inside a text box.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

text_box_shape = builder.insert_shape(aw.drawing.ShapeType.TEXT_BOX, 150, 100)
text_box = text_box_shape.text_box

# Move the document builder to inside the TextBox and add text.
builder.move_to(text_box_shape.last_paragraph)
builder.writeln("Hello world!")
builder.write("Hello again!")

# Set the "layout_flow" property to set an orientation for the text contents of this text box.
text_box.layout_flow = layout_flow

doc.save(ARTIFACTS_DIR + "Shape.text_box_layout_flow.docx")
```

Shows how to get a text box to resize itself to fit its contents tightly.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

text_box_shape = builder.insert_shape(aw.drawing.ShapeType.TEXT_BOX, 150, 100)
text_box = text_box_shape.text_box

# Apply these values to both these members to get the parent shape to fit
# tightly around the text contents, ignoring the dimensions we have set.
text_box.fit_shape_to_text = True
text_box.text_box_wrap_mode = aw.drawing.TextBoxWrapMode.NONE

builder.move_to(text_box_shape.last_paragraph)
builder.write("Text fit tightly inside textbox.")

doc.save(ARTIFACTS_DIR + "Shape.text_box_fit_shape_to_text.docx")
```

Shows how to set internal margins for a text box.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert another textbox with specific margins.
text_box_shape = builder.insert_shape(aw.drawing.ShapeType.TEXT_BOX, 100, 100)
text_box = text_box_shape.text_box
text_box.internal_margin_top = 15
text_box.internal_margin_bottom = 15
text_box.internal_margin_left = 15
text_box.internal_margin_right = 15

builder.move_to(text_box_shape.last_paragraph)
builder.write("Text placed according to textbox margins.")

doc.save(ARTIFACTS_DIR + "Shape.text_box_margins.docx")
```

### See Also

* module [aspose.words.drawing](../)
* property [Shape.text_box](../shape/text_box/)

