﻿---
title: load_format property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the format of the document to be loaded"
type: docs
weight: 90
url: /python-net/aspose.words.loading/loadoptions/load_format/
---

## LoadOptions.load_format property

Specifies the format of the document to be loaded.
Default is [LoadFormat.AUTO](../../../aspose.words/loadformat/#AUTO).


It is recommended that you specify the [LoadFormat.AUTO](../../../aspose.words/loadformat/#AUTO) value and let Aspose.Words detect
the file format automatically. If you know the format of the document you are about to load, you can specify the format
explicitly and this will slightly reduce the loading time by the overhead associated with auto detecting the format.
If you specify an explicit load format and it will turn out to be wrong, the auto detection will be invoked and a second
attempt to load the file will be made.




### Examples

Shows how to specify a base URI when opening an html document.

```python
# Suppose we want to load an .html document that contains an image linked by a relative URI
# while the image is in a different location. In that case, we will need to resolve the relative URI into an absolute one.
# We can provide a base URI using an HtmlLoadOptions object.
load_options = aw.loading.HtmlLoadOptions(aw.LoadFormat.HTML, "", IMAGE_DIR)

self.assertEqual(aw.LoadFormat.HTML, load_options.load_format)

doc = aw.Document(MY_DIR + "Missing image.html", load_options)

# While the image was broken in the input .html, our custom base URI helped us repair the link.
image_shape = doc.get_child_nodes(aw.NodeType.SHAPE, True)[0].as_shape()
self.assertTrue(image_shape.is_image)

# This output document will display the image that was missing.
doc.save(ARTIFACTS_DIR + "HtmlLoadOptions.base_uri.docx")
```

### See Also

* module [aspose.words.loading](../../)
* class [LoadOptions](../)

