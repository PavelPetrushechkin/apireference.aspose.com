﻿---
title: result property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets text that is between the field separator and field end."
type: docs
weight: 70
url: /python-net/aspose.words.fields/field/result/
---

## Field.result property

Gets or sets text that is between the field separator and field end.


### Examples

Shows how to insert a field into a document using a field code.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

field = builder.insert_field("DATE \\@ \"dddd, MMMM dd, yyyy\"")

self.assertEqual(aw.fields.FieldType.FIELD_DATE, field.type)
self.assertEqual("DATE \\@ \"dddd, MMMM dd, yyyy\"", field.get_field_code())

# This overload of the "insert_field" method automatically updates inserted fields.
self.assertAlmostEqual(datetime.strptime(field.result, "%A, %B %d, %Y"), datetime.now(), delta=timedelta(1))
```

### See Also

* module [aspose.words.fields](../../)
* class [Field](../)

