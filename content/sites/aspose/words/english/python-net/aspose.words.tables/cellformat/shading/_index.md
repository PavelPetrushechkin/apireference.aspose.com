﻿---
title: shading property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns a Shading object that refers to the shading formatting for the cell."
type: docs
weight: 90
url: /python-net/aspose.words.tables/cellformat/shading/
---

## CellFormat.shading property

Returns a Shading object that refers to the shading formatting for the cell.


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

Shows how to modify the format of rows and cells in a table.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

table = builder.start_table()
builder.insert_cell()
builder.write("City")
builder.insert_cell()
builder.write("Country")
builder.end_row()
builder.insert_cell()
builder.write("London")
builder.insert_cell()
builder.write("U.K.")
builder.end_table()

# Use the first row's "row_format" property to modify the formatting
# of the contents of all cells in this row.
row_format = table.first_row.row_format
row_format.height = 25
row_format.borders.bottom.color = drawing.Color.red

# Use the "cell_format" property of the first cell in the last row to modify the formatting of that cell's contents.
cell_format = table.last_row.first_cell.cell_format
cell_format.width = 100
cell_format.shading.background_pattern_color = drawing.Color.orange

doc.save(ARTIFACTS_DIR + "Table.row_cell_format.docx")
```

### See Also

* module [aspose.words.tables](../../)
* class [CellFormat](../)

