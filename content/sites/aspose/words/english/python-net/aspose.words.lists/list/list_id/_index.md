﻿---
title: list_id property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets the unique identifier of the list."
type: docs
weight: 60
url: /python-net/aspose.words.lists/list/list_id/
---

## List.list_id property

Gets the unique identifier of the list.

You do not normally need to use this property. But if you use it, you normally do so
in conjunction with the [ListCollection.get_list_by_list_id()](../../listcollection/get_list_by_list_id/#int) method to find a
list by its identifier.




### Examples

Shows how to output all paragraphs in a document that are list items.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.list_format.apply_number_default()
builder.writeln("Numbered list item 1")
builder.writeln("Numbered list item 2")
builder.writeln("Numbered list item 3")
builder.list_format.remove_numbers()

builder.list_format.apply_bullet_default()
builder.writeln("Bulleted list item 1")
builder.writeln("Bulleted list item 2")
builder.writeln("Bulleted list item 3")
builder.list_format.remove_numbers()

paras = doc.get_child_nodes(aw.NodeType.PARAGRAPH, True)

for para in paras:
    para = para.as_paragraph()
    if para.list_format.is_list_item:
        print(f"This paragraph belongs to list ID# {para.list_format.list.list_id}, number style \"{para.list_format.list_level.number_style}\"")
        print(f"\t\"{para.get_text().strip()}\"")
```

Shows how to verify owner document properties of lists.

```python
doc = aw.Document()

lists = doc.lists

self.assertEqual(doc, lists.document)

list = lists.add(aw.lists.ListTemplate.BULLET_DEFAULT)

self.assertEqual(doc, list.document)

print("Current list count:", lists.count)
print("Is the first document list:", lists[0] is list)
print("List id:", list.list_id)
print("List is the same by list_id:", lists.get_list_by_list_id(1) is list)
```

### See Also

* module [aspose.words.lists](../../)
* class [List](../)

