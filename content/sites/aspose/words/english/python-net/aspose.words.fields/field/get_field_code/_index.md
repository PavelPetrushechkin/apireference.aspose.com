﻿---
title: get_field_code method
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.fields.Field.get_field_code method"
type: docs
weight: 1060
url: /python-net/aspose.words.fields/field/get_field_code/
---

## get_field_code() {#default}

Returns text between field start and field separator (or field end if there is no separator).
Both field code and field result of child fields are included.


```python
def get_field_code(self):
    ...
```

## get_field_code(include_child_field_codes) {#bool}

Returns text between field start and field separator (or field end if there is no separator).


```python
def get_field_code(self, include_child_field_codes: bool):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| include_child_field_codes | bool |  |

## Examples

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

Shows how to get a field's field code.

```python
# Open a document which contains a MERGEFIELD inside an IF field.
doc = aw.Document(MY_DIR + "Nested fields.docx")
field_if = doc.range.fields[0].as_field_if()

# There are two ways of getting a field's field code:
# 1 -  Omit its inner fields:
self.assertEqual(" IF  > 0 \" (surplus of ) \" \"\" ", field_if.get_field_code(False))

# 2 -  Include its inner fields:
self.assertEqual(" IF \u0013 MERGEFIELD NetIncome \u0014\u0015 > 0 \" (surplus of \u0013 MERGEFIELD  NetIncome \\f $ \u0014\u0015) \" \"\" ",
    field_if.get_field_code(True))

# By default, the "get_field_code" method displays inner fields.
self.assertEqual(field_if.get_field_code(), field_if.get_field_code(True))
```

## See Also

* module [aspose.words.fields](../../)
* class [Field](../)

