﻿---
title: name property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets name of the ActiveX control."
type: docs
weight: 20
url: /python-net/aspose.words.drawing.ole/olecontrol/name/
---

## OleControl.name property

Gets name of the ActiveX control.


### Examples

Shows how to verify the properties of an ActiveX control.

```python
doc = aw.Document(MY_DIR + "ActiveX controls.docx")

shape = doc.get_child(aw.NodeType.SHAPE, 0, True).as_shape()
ole_control = shape.ole_format.ole_control

self.assertIsNone(ole_control.name)

if ole_control.is_forms2_ole_control:

    check_box = ole_control.as_forms2_ole_control()
    self.assertEqual("Первый", check_box.caption)
    self.assertEqual("0", check_box.value)
    self.assertEqual(True, check_box.enabled)
    self.assertEqual(aw.drawing.ole.Forms2OleControlType.CHECK_BOX, check_box.type)
    self.assertIsNone(check_box.child_nodes)
```

### See Also

* module [aspose.words.drawing.ole](../../)
* class [OleControl](../)

