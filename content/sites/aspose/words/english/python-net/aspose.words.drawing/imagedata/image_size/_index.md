﻿---
title: image_size property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets the information about image size and resolution."
type: docs
weight: 130
url: /python-net/aspose.words.drawing/imagedata/image_size/
---

## ImageData.image_size property

Gets the information about image size and resolution.

If the image is linked only and not stored in the document, returns zero size.




### Examples

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
* class [ImageData](../)

