﻿---
title: is_washout property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets a boolean value which is responsible for washout effect of the watermark"
type: docs
weight: 20
url: /python-net/aspose.words/imagewatermarkoptions/is_washout/
---

## ImageWatermarkOptions.is_washout property

Gets or sets a boolean value which is responsible for washout effect of the watermark.
The default value is True.


### Examples

Shows how to create a watermark from an image in the local file system.

```python
doc = aw.Document()

# Modify the image watermark's appearance with an ImageWatermarkOptions object,
# then pass it while creating a watermark from an image file.
image_watermark_options = aw.ImageWatermarkOptions()
image_watermark_options.scale = 5
image_watermark_options.is_washout = False

doc.watermark.set_image(drawing.Image.from_file(IMAGE_DIR + "Logo.jpg"), image_watermark_options)

doc.save(ARTIFACTS_DIR + "Document.image_watermark.docx")
```

### See Also

* module [aspose.words](../../)
* class [ImageWatermarkOptions](../)

