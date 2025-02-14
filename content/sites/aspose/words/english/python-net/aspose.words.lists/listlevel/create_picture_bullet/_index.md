﻿---
title: create_picture_bullet method
second_title: Aspose.Words for Python via .NET API Reference
description: "Creates picture bullet shape for the current list level."
type: docs
weight: 150
url: /python-net/aspose.words.lists/listlevel/create_picture_bullet/
---

## create_picture_bullet() {#default}

Creates picture bullet shape for the current list level.


```python
def create_picture_bullet(self):
    ...
```

Please note, NumberStyle will be set to Bullet and 
NumberFormat to "\\xF0B7" to properly display picture bullet.
Red cross image will be set as picture bullet image upon creating. 
To change it please use [ListLevel.image_data](../image_data/).


### Examples

Shows how to set a custom image icon for list item labels.

```python
doc = aw.Document()

list = doc.lists.add(aw.lists.ListTemplate.BULLET_CIRCLE)

# Create a picture bullet for the current list level, and set an image from a local file system
# as the icon that the bullets for this list level will display.
list.list_levels[0].create_picture_bullet()
list.list_levels[0].image_data.set_image(IMAGE_DIR + "Logo icon.ico")

self.assertTrue(list.list_levels[0].image_data.has_image)

builder = aw.DocumentBuilder(doc)

builder.list_format.list = list
builder.writeln("Hello world!")
builder.write("Hello again!")

doc.save(ARTIFACTS_DIR + "Lists.create_picture_bullet.docx")

list.list_levels[0].delete_picture_bullet()

self.assertIsNone(list.list_levels[0].image_data)
```

### See Also

* module [aspose.words.lists](../../)
* class [ListLevel](../)

