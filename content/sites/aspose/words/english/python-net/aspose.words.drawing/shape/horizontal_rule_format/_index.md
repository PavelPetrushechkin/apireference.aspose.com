﻿---
title: horizontal_rule_format property
second_title: Aspose.Words for Python via .NET API Reference
description: "Provides access to the properties of the horizontal rule shape"
type: docs
weight: 100
url: /python-net/aspose.words.drawing/shape/horizontal_rule_format/
---

## Shape.horizontal_rule_format property

Provides access to the properties of the horizontal rule shape.
For a shape that is not a horizontal rule, returns null.


### Examples

Shows how to insert a horizontal rule shape, and customize its formatting.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
shape = builder.insert_horizontal_rule()

horizontal_rule_format = shape.horizontal_rule_format
horizontal_rule_format.alignment = aw.drawing.HorizontalRuleAlignment.CENTER
horizontal_rule_format.width_percent = 70
horizontal_rule_format.height = 3
horizontal_rule_format.color = drawing.Color.blue
horizontal_rule_format.no_shade = True

self.assertTrue(shape.is_horizontal_rule)
self.assertTrue(shape.horizontal_rule_format.no_shade)
```

### See Also

* module [aspose.words.drawing](../../)
* class [Shape](../)

