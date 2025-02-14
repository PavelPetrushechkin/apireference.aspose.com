﻿---
title: width property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the width of the containing block of the shape."
type: docs
weight: 520
url: /python-net/aspose.words.drawing/shapebase/width/
---

## ShapeBase.width property

Gets or sets the width of the containing block of the shape.

For a top-level shape, the value is in points.

For shapes in a group, the value is in the coordinate space and units of the parent group.

The default value is 0.




### Examples

Shows how to insert a floating image, and specify its position and size.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

shape = builder.insert_image(IMAGE_DIR + "Logo.jpg")
shape.wrap_type = aw.drawing.WrapType.NONE

# Configure the shape's "relative_horizontal_position" property to treat the value of the "left" property
# as the shape's horizontal distance, in points, from the left side of the page.
shape.relative_horizontal_position = aw.drawing.RelativeHorizontalPosition.PAGE

# Set the shape's horizontal distance from the left side of the page to 100.
shape.left = 100

# Use the "relative_vertical_position" property in a similar way to position the shape 80pt below the top of the page.
shape.relative_vertical_position = aw.drawing.RelativeVerticalPosition.PAGE
shape.top = 80

# Set the shape's height, which will automatically scale the width to preserve dimensions.
shape.height = 125

self.assertEqual(125.0, shape.width)

# The "bottom" and "right" properties contain the bottom and right edges of the image.
self.assertEqual(shape.top + shape.height, shape.bottom)
self.assertEqual(shape.left + shape.width, shape.right)

doc.save(ARTIFACTS_DIR + "Image.create_floating_position_size.docx")
```

Shows how to resize a shape with an image.

```python
image = drawing.Image.from_file(IMAGE_DIR + "Logo.jpg")

self.assertEqual(400, image.size.width)
self.assertEqual(400, image.size.height)

# When we insert an image using the "insert_image" method, the builder scales the shape that displays the image so that,
# when we view the document using 100% zoom in Microsoft Word, the shape displays the image in its actual size.
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
shape = builder.insert_image(IMAGE_DIR + "Logo.jpg")

# A 400x400 image will create an ImageData object with an image size of 300x300pt.
image_size = shape.image_data.image_size

self.assertEqual(300.0, image_size.width_points)
self.assertEqual(300.0, image_size.height_points)

# If a shape's dimensions match the image data's dimensions,
# then the shape is displaying the image in its original size.
self.assertEqual(300.0, shape.width)
self.assertEqual(300.0, shape.height)

# Reduce the overall size of the shape by 50%.
shape.width *= 0.5

# Scaling factors apply to both the width and the height at the same time to preserve the shape's proportions.
self.assertEqual(150.0, shape.width)
self.assertEqual(150.0, shape.height)

# When we resize the shape, the size of the image data remains the same.
self.assertEqual(300.0, image_size.width_points)
self.assertEqual(300.0, image_size.height_points)

# We can reference the image data dimensions to apply a scaling based on the size of the image.
shape.width = image_size.width_points * 1.1

self.assertEqual(330.0, shape.width)
self.assertEqual(330.0, shape.height)

doc.save(ARTIFACTS_DIR + "Image.scale_image.docx")
```

### See Also

* module [aspose.words.drawing](../../)
* class [ShapeBase](../)

