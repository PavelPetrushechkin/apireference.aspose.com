﻿---
title: ChartNumberFormat class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents number formatting of the parent element."
type: docs
weight: 230
url: /python-net/aspose.words.drawing.charts/chartnumberformat/
---

## ChartNumberFormat class

Represents number formatting of the parent element.


### Properties

| Name | Description |
| --- | --- |
| [format_code](./format_code/) | Gets or sets the format code applied to a data label. |
| [is_linked_to_source](./is_linked_to_source/) | Specifies whether the format code is linked to a source cell. Default is true. |

### Examples

Shows how to set formatting for chart values.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

shape = builder.insert_chart(aw.drawing.charts.ChartType.COLUMN, 500, 300)
chart = shape.chart

# Clear the chart's demo data series to start with a clean chart.
chart.series.clear()

# Add a custom series to the chart with categories for the X-axis,
# and large respective numeric values for the Y-axis.
chart.series.add("Aspose Test Series",
    ["Word", "PDF", "Excel", "GoogleDocs", "Note"],
    [1900000, 850000, 2100000, 600000, 1500000])

# Set the number format of the Y-axis tick labels to not group digits with commas.
chart.axis_y.number_format.format_code = "#,##0"

# This flag can override the above value and draw the number format from the source cell.
self.assertFalse(chart.axis_y.number_format.is_linked_to_source)

doc.save(ARTIFACTS_DIR + "Charts.set_number_format_to_chart_axis.docx")
```

### See Also

* module [aspose.words.drawing.charts](../)

