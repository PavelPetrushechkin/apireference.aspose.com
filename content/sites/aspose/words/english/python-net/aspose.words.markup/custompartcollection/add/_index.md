﻿---
title: add method
second_title: Aspose.Words for Python via .NET API Reference
description: "Adds an item to the collection."
type: docs
weight: 40
url: /python-net/aspose.words.markup/custompartcollection/add/
---

## add(part) {#custompart}

Adds an item to the collection.


```python
def add(self, part: aspose.words.markup.CustomPart):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| part | [CustomPart](../../custompart/) |  |

### Examples

Shows how to access a document's arbitrary custom parts collection.

```python
doc = aw.Document(MY_DIR + "Custom parts OOXML package.docx")

self.assertEqual(2, doc.package_custom_parts.count)

# Clone the second part, then add the clone to the collection.
cloned_part = doc.package_custom_parts[1].clone()
doc.package_custom_parts.add(cloned_part)

self.assertEqual(3, doc.package_custom_parts.count)

# Enumerate over the collection and print every part.
for index, part in enumerate(doc.package_custom_parts):
    print(f"Part index {index}:")
    print(f"\tName:\t\t\t\t{part.name}")
    print(f"\tContent type:\t\t{part.content_type}")
    print(f"\tRelationship type:\t{part.relationship_type}")
    if part.is_external:
        print("\tSourced from outside the document")
    else:
        print(f"\tStored within the document, length: {len(part.data)} bytes")

# We can remove elements from this collection individually, or all at once.
doc.package_custom_parts.remove_at(2)

self.assertEqual(2, doc.package_custom_parts.count)

doc.package_custom_parts.clear()

self.assertEqual(0, doc.package_custom_parts.count)
```

### See Also

* module [aspose.words.markup](../../)
* class [CustomPartCollection](../)

