﻿---
title: equals method
second_title: Aspose.Words for Python via .NET API Reference
description: "Compares collections of borders."
type: docs
weight: 150
url: /python-net/aspose.words/bordercollection/equals/
---

## equals(br_coll) {#bordercollection}

Compares collections of borders.


```python
def equals(self, br_coll: aspose.words.BorderCollection):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| br_coll | [BorderCollection](../) |  |

### Examples

Shows how border collections can share elements.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.writeln("Paragraph 1.")
builder.write("Paragraph 2.")

# Since we used the same border configuration while creating
# these paragraphs, their border collections share the same elements.
first_paragraph_borders = doc.first_section.body.first_paragraph.paragraph_format.borders
second_paragraph_borders = builder.current_paragraph.paragraph_format.borders

for i in range(first_paragraph_borders.count):
    self.assertEqual(first_paragraph_borders[i], second_paragraph_borders[i])
    self.assertFalse(first_paragraph_borders[i].is_visible)

for border in second_paragraph_borders:
    border.line_style = aw.LineStyle.DOT_DASH

# After changing the line style of the borders in just the second paragraph,
# the border collections no longer share the same elements.
for i in range(first_paragraph_borders.count):
    self.assertNotEqual(first_paragraph_borders[i], second_paragraph_borders[i])

    # Changing the appearance of an empty border makes it visible.
    self.assertTrue(second_paragraph_borders[i].is_visible)

doc.save(ARTIFACTS_DIR + "Border.shared_elements.docx")
```

### See Also

* module [aspose.words](../../)
* class [BorderCollection](../)

