﻿---
title: FieldFootnoteRef class
second_title: Aspose.Words for Python via .NET API Reference
description: "Implements the FOOTNOTEREF field."
type: docs
weight: 440
url: /python-net/aspose.words.fields/fieldfootnoteref/
---

## FieldFootnoteRef class

Implements the FOOTNOTEREF field.


**Inheritance:** [FieldFootnoteRef](./) → [Field](../field/)

### Constructors
| Name | Description |
| --- | --- |
| [FieldFootnoteRef()](./__init__/#default) | The default constructor. |

### Properties

| Name | Description |
| --- | --- |
| [display_result](../field/display_result/) | Gets the text that represents the displayed field result.<br>(Inherited from [Field](../field/)) |
| [end](../field/end/) | Gets the node that represents the field end.<br>(Inherited from [Field](../field/)) |
| [format](../field/format/) | Gets a [FieldFormat](../fieldformat/) object that provides typed access to field's formatting.<br>(Inherited from [Field](../field/)) |
| [is_dirty](../field/is_dirty/) | Gets or sets whether the current result of the field is no longer correct (stale) due to other modifications made to the document.<br>(Inherited from [Field](../field/)) |
| [is_locked](../field/is_locked/) | Gets or sets whether the field is locked (should not recalculate its result).<br>(Inherited from [Field](../field/)) |
| [locale_id](../field/locale_id/) | Gets or sets the LCID of the field.<br>(Inherited from [Field](../field/)) |
| [result](../field/result/) | Gets or sets text that is between the field separator and field end.<br>(Inherited from [Field](../field/)) |
| [separator](../field/separator/) | Gets the node that represents the field separator. Can be null.<br>(Inherited from [Field](../field/)) |
| [start](../field/start/) | Gets the node that represents the start of the field.<br>(Inherited from [Field](../field/)) |
| [type](../field/type/) | Gets the Microsoft Word field type.<br>(Inherited from [Field](../field/)) |

### Methods

| Name | Description |
| --- | --- |
|[ get_field_code()](../field/get_field_code/#default) | Returns text between field start and field separator (or field end if there is no separator). Both field code and field result of child fields are included.<br>(Inherited from [Field](../field/)) |
|[ get_field_code(include_child_field_codes)](../field/get_field_code/#bool) | Returns text between field start and field separator (or field end if there is no separator).<br>(Inherited from [Field](../field/)) |
|[ remove()](../field/remove/#default) | Removes the field from the document. Returns a node right after the field. If the field's end is the last child of its parent node, returns its parent paragraph. If the field is already removed, returns **null**.<br>(Inherited from [Field](../field/)) |
|[ unlink()](../field/unlink/#default) | Performs the field unlink.<br>(Inherited from [Field](../field/)) |
|[ update()](../field/update/#default) | Performs the field update. Throws if the field is being updated already.<br>(Inherited from [Field](../field/)) |
|[ update(ignore_merge_format)](../field/update/#bool) | Performs a field update. Throws if the field is being updated already.<br>(Inherited from [Field](../field/)) |

### Examples

Shows how to cross-reference footnotes with the FOOTNOTEREF field.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.start_bookmark("CrossRefBookmark")
builder.write("Hello world!")
builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Cross referenced footnote.")
builder.end_bookmark("CrossRefBookmark")
builder.insert_paragraph()

# Insert a FOOTNOTEREF field, which lets us reference a footnote more than once while re-using the same footnote marker.
builder.write("CrossReference: ")
field = builder.insert_field(aw.fields.FieldType.FIELD_FOOTNOTE_REF, True).as_field_footnote_ref()

# Reference the bookmark that we have created with the FOOTNOTEREF field. That bookmark contains a footnote marker
# belonging to the footnote we inserted. The field will display that footnote marker.
builder.move_to(field.separator)
builder.write("CrossRefBookmark")

self.assertEqual(" FOOTNOTEREF CrossRefBookmark", field.get_field_code())

doc.update_fields()

# This field works only in older versions of Microsoft Word.
doc.save(ARTIFACTS_DIR + "Field.field_footnote_ref.doc")
```

### See Also

* module [aspose.words.fields](../)
* class [Field](../field/)

