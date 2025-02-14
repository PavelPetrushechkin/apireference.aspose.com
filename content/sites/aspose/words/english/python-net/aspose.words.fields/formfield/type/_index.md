﻿---
title: type property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns the form field type."
type: docs
weight: 220
url: /python-net/aspose.words.fields/formfield/type/
---

## FormField.type property

Returns the form field type.


### Examples

Shows how to insert a combo box.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.write("Please select a fruit: ")

# Insert a combo box which will allow a user to choose an option from a collection of strings.
combo_box = builder.insert_combo_box("MyComboBox", ["Apple", "Banana", "Cherry"], 0)

self.assertEqual("MyComboBox", combo_box.name)
self.assertEqual(aw.fields.FieldType.FIELD_FORM_DROP_DOWN, combo_box.type)
self.assertEqual("Apple", combo_box.result)

# The form field will appear in the form of a "select" html tag.
doc.save(ARTIFACTS_DIR + "FormFields.create.html")
```

### See Also

* module [aspose.words.fields](../../)
* class [FormField](../)

