﻿---
title: style_identifier property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the locale independent style identifier of the table style applied to this table."
type: docs
weight: 280
url: /python-net/aspose.words.tables/table/style_identifier/
---

## Table.style_identifier property

Gets or sets the locale independent style identifier of the table style applied to this table.


### Examples

Shows how to build a new table while applying a style.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
table = builder.start_table()

# We must insert at least one row before setting any table formatting.
builder.insert_cell()

# Set the table style used based on the style identifier.
# Note that not all table styles are available when saving to .doc format.
table.style_identifier = aw.StyleIdentifier.MEDIUM_SHADING1_ACCENT1

# Partially apply the style to features of the table based on predicates, then build the table.
table.style_options = aw.tables.TableStyleOptions.FIRST_COLUMN | aw.tables.TableStyleOptions.ROW_BANDS | aw.tables.TableStyleOptions.FIRST_ROW
table.auto_fit(aw.tables.AutoFitBehavior.AUTO_FIT_TO_CONTENTS)

builder.writeln("Item")
builder.cell_format.right_padding = 40
builder.insert_cell()
builder.writeln("Quantity (kg)")
builder.end_row()

builder.insert_cell()
builder.writeln("Apples")
builder.insert_cell()
builder.writeln("20")
builder.end_row()

builder.insert_cell()
builder.writeln("Bananas")
builder.insert_cell()
builder.writeln("40")
builder.end_row()

builder.insert_cell()
builder.writeln("Carrots")
builder.insert_cell()
builder.writeln("50")
builder.end_row()

doc.save(ARTIFACTS_DIR + "DocumentBuilder.insert_table_with_style.docx")
```

### See Also

* module [aspose.words.tables](../../)
* class [Table](../)

