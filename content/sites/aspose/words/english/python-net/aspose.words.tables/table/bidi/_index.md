﻿---
title: bidi property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets whether this is a right-to-left table."
type: docs
weight: 80
url: /python-net/aspose.words.tables/table/bidi/
---

## Table.bidi property

Gets or sets whether this is a right-to-left table.

When ``true``, the cells in this row are laid out right to left.

The default value is ``false``.




### Examples

Shows how to create custom style settings for the table.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

table = builder.start_table()
builder.insert_cell()
builder.write("Name")
builder.insert_cell()
builder.write("مرحبًا")
builder.end_row()
builder.insert_cell()
builder.insert_cell()
builder.end_table()

table_style = doc.styles.add(aw.StyleType.TABLE, "MyTableStyle1").as_table_style()
table_style.allow_break_across_pages = True
table_style.bidi = True
table_style.cell_spacing = 5
table_style.bottom_padding = 20
table_style.left_padding = 5
table_style.right_padding = 10
table_style.top_padding = 20
table_style.shading.background_pattern_color = drawing.Color.antique_white
table_style.borders.color = drawing.Color.blue
table_style.borders.line_style = aw.LineStyle.DOT_DASH
table_style.vertical_alignment = aw.tables.CellVerticalAlignment.CENTER

table.style = table_style

# Setting the style properties of a table may affect the properties of the table itself.
self.assertTrue(table.bidi)
self.assertEqual(5.0, table.cell_spacing)
self.assertEqual("MyTableStyle1", table.style_name)

doc.save(ARTIFACTS_DIR + "Table.table_style_creation.docx")
```

### See Also

* module [aspose.words.tables](../../)
* class [Table](../)

