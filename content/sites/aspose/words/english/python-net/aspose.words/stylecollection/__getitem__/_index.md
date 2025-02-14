﻿---
title: StyleCollection indexer
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets a style by index."
type: docs
weight: 10
url: /python-net/aspose.words/stylecollection/__getitem__/
---

## \_\_getitem\_\_(index) {#int}

Gets a style by index.


```python
def __getitem__(self, index: int):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

### Examples

Shows how to add a Style to a document's styles collection.

```python
doc = aw.Document()
styles = doc.styles

# Set default parameters for new styles that we may later add to this collection.
styles.default_font.name = "Courier New"

# If we add a style of the "StyleType.PARAGRAPH", the collection will apply the values of
# its "default_paragraph_format" property to the style's "paragraph_format" property.
styles.default_paragraph_format.first_line_indent = 15.0

# Add a style, and then verify that it has the default settings.
styles.add(aw.StyleType.PARAGRAPH, "MyStyle")

self.assertEqual("Courier New", styles[4].font.name)
self.assertEqual(15.0, styles.get_by_name("MyStyle").paragraph_format.first_line_indent)
```

### See Also

* module [aspose.words](../../)
* class [StyleCollection](../)

