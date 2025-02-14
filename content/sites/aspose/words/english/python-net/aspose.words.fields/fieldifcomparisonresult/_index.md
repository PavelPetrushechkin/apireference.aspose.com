﻿---
title: FieldIfComparisonResult enumeration
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the result of the IF field condition evaluation."
type: docs
weight: 550
url: /python-net/aspose.words.fields/fieldifcomparisonresult/
---

## FieldIfComparisonResult enumeration

Specifies the result of the IF field condition evaluation.


### Members

| Name | Description |
| --- | --- |
| ERROR | There is an error in the condition. |
| TRUE | The condition is ``true``. |
| FALSE | The condition is ``false``. |

### Examples

Shows how to insert an IF field.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.write("Statement 1: ")
field = builder.insert_field(aw.fields.FieldType.FIELD_IF, True).as_field_if()
field.left_expression = "0"
field.comparison_operator = "="
field.right_expression = "1"

# The IF field will display a string from either its "true_text" property,
# or its "false_text" property, depending on the truth of the statement that we have constructed.
field.true_text = "True"
field.false_text = "False"
field.update()

# In this case, "0 = 1" is incorrect, so the displayed result will be "False".
self.assertEqual(" IF  0 = 1 True False", field.get_field_code())
self.assertEqual(aw.fields.FieldIfComparisonResult.FALSE, field.evaluate_condition())
self.assertEqual("False", field.result)

builder.write("\nStatement 2: ")
field = builder.insert_field(aw.fields.FieldType.FIELD_IF, True).as_field_if()
field.left_expression = "5"
field.comparison_operator = "="
field.right_expression = "2 + 3"
field.true_text = "True"
field.false_text = "False"
field.update()

# This time the statement is correct, so the displayed result will be "True".
self.assertEqual(" IF  5 = \"2 + 3\" True False", field.get_field_code())
self.assertEqual(aw.fields.FieldIfComparisonResult.TRUE, field.evaluate_condition())
self.assertEqual("True", field.result)

doc.update_fields()
doc.save(ARTIFACTS_DIR + "Field.field_if.docx")
```

### See Also

* module [aspose.words.fields](../)

