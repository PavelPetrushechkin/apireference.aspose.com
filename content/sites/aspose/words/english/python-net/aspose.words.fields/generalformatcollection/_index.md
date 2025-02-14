﻿---
title: GeneralFormatCollection class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents a typed collection of general formats."
type: docs
weight: 1180
url: /python-net/aspose.words.fields/generalformatcollection/
---

## GeneralFormatCollection class

Represents a typed collection of general formats.


### Indexers

| Name | Description |
| --- | --- |
| [``__getitem__(index)``](./__getitem__/#int) | Gets a general format at the specified index. |

### Properties

| Name | Description |
| --- | --- |
| [count](./count/) | Gets the total number of the items in the collection. |

### Methods

| Name | Description |
| --- | --- |
|[ add(item)](./add/#generalformat) | Adds a general format to the collection. |
|[ remove(item)](./remove/#generalformat) | Removes all occurrences of the specified general format from the collection. |
|[ remove_at(index)](./remove_at/#int) | Removes a general format occurrence at the specified index. |

### Examples

Shows how to format field results.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Use a document builder to insert a field that displays a result with no format applied.
field = builder.insert_field("= 2 + 3")

self.assertEqual("= 2 + 3", field.get_field_code())
self.assertEqual("5", field.result)

# We can apply a format to a field's result using the field's properties.
# Below are three types of formats that we can apply to a field's result.
# 1 -  Numeric format:
format = field.format
format.numeric_format = "$###.00"
field.update()

self.assertEqual("= 2 + 3 \\# $###.00", field.get_field_code())
self.assertEqual("$  5.00", field.result)

# 2 -  Date/time format:
field = builder.insert_field("DATE")
format = field.format
format.date_time_format = "dddd, MMMM dd, yyyy"
field.update()

self.assertEqual("DATE \\@ \"dddd, MMMM dd, yyyy\"", field.get_field_code())
print(f"Today's date, in {format.date_time_format} format:\n\t{field.result}")

# 3 -  General format:
field = builder.insert_field("= 25 + 33")
format = field.format
format.general_formats.add(aw.fields.GeneralFormat.LOWERCASE_ROMAN)
format.general_formats.add(aw.fields.GeneralFormat.UPPER)
field.update()

for index, general_format in enumerate(format.general_formats):
    print(f"General format index {index}: {general_format}")

self.assertEqual("= 25 + 33 \\* roman \\* Upper", field.get_field_code())
self.assertEqual("LVIII", field.result)
self.assertEqual(2, format.general_formats.count)
self.assertEqual(aw.fields.GeneralFormat.LOWERCASE_ROMAN, format.general_formats[0])

# We can remove our formats to revert the field's result to its original form.
format.general_formats.remove(aw.fields.GeneralFormat.LOWERCASE_ROMAN)
format.general_formats.remove_at(0)
self.assertEqual(0, format.general_formats.count)
field.update()

self.assertEqual("= 25 + 33  ", field.get_field_code())
self.assertEqual("58", field.result)
self.assertEqual(0, format.general_formats.count)
```

### See Also

* module [aspose.words.fields](../)

