﻿---
title: is_top_level property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns true if this shape is not a child of a group shape."
type: docs
weight: 340
url: /python-net/aspose.words.drawing/shapebase/is_top_level/
---

## ShapeBase.is_top_level property

Returns true if this shape is not a child of a group shape.


### Examples

Shows how to tell whether a shape is a part of a group shape.

```python
doc = aw.Document()

shape = aw.drawing.Shape(doc, aw.drawing.ShapeType.RECTANGLE)
shape.width = 200
shape.height = 200
shape.wrap_type = aw.drawing.WrapType.NONE

# A shape by default is not part of any group shape, and therefore has the "is_top_level" property set to "True".
self.assertTrue(shape.is_top_level)

group = aw.drawing.GroupShape(doc)
group.append_child(shape)

# Once we assimilate a shape into a group shape, the "is_top_level" property changes to "False".
self.assertFalse(shape.is_top_level)
```

### See Also

* module [aspose.words.drawing](../../)
* class [ShapeBase](../)

