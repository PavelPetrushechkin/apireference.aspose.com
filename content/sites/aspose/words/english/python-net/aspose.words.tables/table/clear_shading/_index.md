﻿---
title: clear_shading method
second_title: Aspose.Words for Python via .NET API Reference
description: "Removes all shading on the table."
type: docs
weight: 380
url: /python-net/aspose.words.tables/table/clear_shading/
---

## clear_shading() {#default}

Removes all shading on the table.


```python
def clear_shading(self):
    ...
```

### Examples

Shows how to apply an outline border to a table.

```python
doc = aw.Document(MY_DIR + "Tables.docx")
table = doc.first_section.body.tables[0]

# Align the table to the center of the page.
table.alignment = aw.tables.TableAlignment.CENTER

# Clear any existing borders and shading from the table.
table.clear_borders()
table.clear_shading()

# Add green borders to the outline of the table.
table.set_border(aw.BorderType.LEFT, aw.LineStyle.SINGLE, 1.5, drawing.Color.green, True)
table.set_border(aw.BorderType.RIGHT, aw.LineStyle.SINGLE, 1.5, drawing.Color.green, True)
table.set_border(aw.BorderType.TOP, aw.LineStyle.SINGLE, 1.5, drawing.Color.green, True)
table.set_border(aw.BorderType.BOTTOM, aw.LineStyle.SINGLE, 1.5, drawing.Color.green, True)

# Fill the cells with a light green solid color.
table.set_shading(aw.TextureIndex.TEXTURE_SOLID, drawing.Color.light_green, drawing.Color.empty())

doc.save(ARTIFACTS_DIR + "Table.set_outline_borders.docx")
```

### See Also

* module [aspose.words.tables](../../)
* class [Table](../)

