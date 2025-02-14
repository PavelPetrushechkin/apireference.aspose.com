﻿---
title: end_table method
second_title: Aspose.Words for Python via .NET API Reference
description: "Ends a table in the document."
type: docs
weight: 230
url: /python-net/aspose.words/documentbuilder/end_table/
---

## end_table() {#default}

Ends a table in the document.


```python
def end_table(self):
    ...
```

This method should be called only once after [DocumentBuilder.end_row()](../end_row/#default) was called. When called,
**EndTable** moves the cursor out of the current cell to point just after the table.




### Returns

The table node that was just finished.


### Examples

Shows how to build a table with custom borders.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.start_table()

# Setting table formatting options for a document builder
# will apply them to every row and cell that we add with it.
builder.paragraph_format.alignment = aw.ParagraphAlignment.CENTER

builder.cell_format.clear_formatting()
builder.cell_format.width = 150
builder.cell_format.vertical_alignment = aw.tables.CellVerticalAlignment.CENTER
builder.cell_format.shading.background_pattern_color = drawing.Color.green_yellow
builder.cell_format.wrap_text = False
builder.cell_format.fit_text = True

builder.row_format.clear_formatting()
builder.row_format.height_rule = aw.HeightRule.EXACTLY
builder.row_format.height = 50
builder.row_format.borders.line_style = aw.LineStyle.ENGRAVE_3D
builder.row_format.borders.color = drawing.Color.orange

builder.insert_cell()
builder.write("Row 1, Col 1")

builder.insert_cell()
builder.write("Row 1, Col 2")
builder.end_row()

# Changing the formatting will apply it to the current cell,
# and any new cells that we create with the builder afterward.
# This will not affect the cells that we have added previously.
builder.cell_format.shading.clear_formatting()

builder.insert_cell()
builder.write("Row 2, Col 1")

builder.insert_cell()
builder.write("Row 2, Col 2")

builder.end_row()

# Increase row height to fit the vertical text.
builder.insert_cell()
builder.row_format.height = 150
builder.cell_format.orientation = aw.TextOrientation.UPWARD
builder.write("Row 3, Col 1")

builder.insert_cell()
builder.cell_format.orientation = aw.TextOrientation.DOWNWARD
builder.write("Row 3, Col 2")

builder.end_row()
builder.end_table()

doc.save(ARTIFACTS_DIR + "DocumentBuilder.insert_table.docx")
```

Shows how to build a formatted 2x2 table.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

table = builder.start_table()
builder.insert_cell()
builder.cell_format.vertical_alignment = aw.tables.CellVerticalAlignment.CENTER
builder.write("Row 1, cell 1.")
builder.insert_cell()
builder.write("Row 1, cell 2.")
builder.end_row()

# While building the table, the document builder will apply its current row_format/cell_format property values
# to the current row/cell that its cursor is in and any new rows/cells as it creates them.
self.assertEqual(aw.tables.CellVerticalAlignment.CENTER, table.rows[0].cells[0].cell_format.vertical_alignment)
self.assertEqual(aw.tables.CellVerticalAlignment.CENTER, table.rows[0].cells[1].cell_format.vertical_alignment)

builder.insert_cell()
builder.row_format.height = 100
builder.row_format.height_rule = aw.HeightRule.EXACTLY
builder.cell_format.orientation = aw.TextOrientation.UPWARD
builder.write("Row 2, cell 1.")
builder.insert_cell()
builder.cell_format.orientation = aw.TextOrientation.DOWNWARD
builder.write("Row 2, cell 2.")
builder.end_row()
builder.end_table()

# Previously added rows and cells are not retroactively affected by changes to the builder's formatting.
self.assertEqual(0, table.rows[0].row_format.height)
self.assertEqual(aw.HeightRule.AUTO, table.rows[0].row_format.height_rule)
self.assertEqual(100, table.rows[1].row_format.height)
self.assertEqual(aw.HeightRule.EXACTLY, table.rows[1].row_format.height_rule)
self.assertEqual(aw.TextOrientation.UPWARD, table.rows[1].cells[0].cell_format.orientation)
self.assertEqual(aw.TextOrientation.DOWNWARD, table.rows[1].cells[1].cell_format.orientation)

doc.save(ARTIFACTS_DIR + "DocumentBuilder.build_table.docx")
```

Shows how to format cells with a document builder.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

table = builder.start_table()
builder.insert_cell()
builder.write("Row 1, cell 1.")

# Insert a second cell, and then configure cell text padding options.
# The builder will apply these settings at its current cell, and any new cells creates afterwards.
builder.insert_cell()

cell_format = builder.cell_format
cell_format.width = 250
cell_format.left_padding = 30
cell_format.right_padding = 30
cell_format.top_padding = 30
cell_format.bottom_padding = 30

builder.write("Row 1, cell 2.")
builder.end_row()
builder.end_table()

# The first cell was unaffected by the padding reconfiguration, and still holds the default values.
self.assertEqual(0.0, table.first_row.cells[0].cell_format.width)
self.assertEqual(5.4, table.first_row.cells[0].cell_format.left_padding)
self.assertEqual(5.4, table.first_row.cells[0].cell_format.right_padding)
self.assertEqual(0.0, table.first_row.cells[0].cell_format.top_padding)
self.assertEqual(0.0, table.first_row.cells[0].cell_format.bottom_padding)

self.assertEqual(250.0, table.first_row.cells[1].cell_format.width)
self.assertEqual(30.0, table.first_row.cells[1].cell_format.left_padding)
self.assertEqual(30.0, table.first_row.cells[1].cell_format.right_padding)
self.assertEqual(30.0, table.first_row.cells[1].cell_format.top_padding)
self.assertEqual(30.0, table.first_row.cells[1].cell_format.bottom_padding)

# The first cell will still grow in the output document to match the size of its neighboring cell.
doc.save(ARTIFACTS_DIR + "DocumentBuilder.set_cell_formatting.docx")
```

### See Also

* module [aspose.words](../../)
* class [DocumentBuilder](../)

