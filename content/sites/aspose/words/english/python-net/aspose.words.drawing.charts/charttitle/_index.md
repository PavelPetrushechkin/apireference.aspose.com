﻿---
title: ChartTitle class
second_title: Aspose.Words for Python via .NET API Reference
description: "Provides access to the chart title properties."
type: docs
weight: 260
url: /python-net/aspose.words.drawing.charts/charttitle/
---

## ChartTitle class

Provides access to the chart title properties.


### Properties

| Name | Description |
| --- | --- |
| [overlay](./overlay/) | Determines whether other chart elements shall be allowed to overlap title. By default overlay is false. |
| [show](./show/) | Determines whether the title shall be shown for this chart. Default value is true. |
| [text](./text/) | Gets or sets the text of the chart title. If null or empty value is specified, auto generated title will be shown. |

### Examples

Shows how to insert a chart and set a title.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert a chart shape with a document builder and get its chart.
chart_shape = builder.insert_chart(aw.drawing.charts.ChartType.BAR, 400, 300)
chart = chart_shape.chart

# Use the "title" property to give our chart a title, which appears at the top center of the chart area.
title = chart.title
title.text = "My Chart"

# Set the "show" property to "True" to make the title visible.
title.show = True

# Set the "overlay" property to "True" Give other chart elements more room by allowing them to overlap the title
title.overlay = True

doc.save(ARTIFACTS_DIR + "Charts.chart_title.docx")
```

### See Also

* module [aspose.words.drawing.charts](../)

