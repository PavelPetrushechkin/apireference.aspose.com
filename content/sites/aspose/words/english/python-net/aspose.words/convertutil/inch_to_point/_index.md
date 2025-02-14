﻿---
title: inch_to_point method
second_title: Aspose.Words for Python via .NET API Reference
description: "Converts inches to points."
type: docs
weight: 10
url: /python-net/aspose.words/convertutil/inch_to_point/
---

## inch_to_point(inches) {#float}

Converts inches to points.


```python
def inch_to_point(self, inches: float):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| inches | float |  |

1 inch equals 72 points.


### Examples

Shows how to adjust paper size, orientation, margins, along with other settings for a section.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.page_setup.paper_size = aw.PaperSize.LEGAL
builder.page_setup.orientation = aw.Orientation.LANDSCAPE
builder.page_setup.top_margin = aw.ConvertUtil.inch_to_point(1.0)
builder.page_setup.bottom_margin = aw.ConvertUtil.inch_to_point(1.0)
builder.page_setup.left_margin = aw.ConvertUtil.inch_to_point(1.5)
builder.page_setup.right_margin = aw.ConvertUtil.inch_to_point(1.5)
builder.page_setup.header_distance = aw.ConvertUtil.inch_to_point(0.2)
builder.page_setup.footer_distance = aw.ConvertUtil.inch_to_point(0.2)

builder.writeln("Hello world!")

doc.save(ARTIFACTS_DIR + "PageSetup.page_margins.docx")
```

Shows how to specify page properties in inches.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# A section's "Page Setup" defines the size of the page margins in points.
# We can also use the "ConvertUtil" class to use a more familiar measurement unit,
# such as inches when defining boundaries.
page_setup = builder.page_setup
page_setup.top_margin = aw.ConvertUtil.inch_to_point(1.0)
page_setup.bottom_margin = aw.ConvertUtil.inch_to_point(2.0)
page_setup.left_margin = aw.ConvertUtil.inch_to_point(2.5)
page_setup.right_margin = aw.ConvertUtil.inch_to_point(1.5)

# An inch is 72 points.
self.assertEqual(72.0, aw.ConvertUtil.inch_to_point(1))
self.assertEqual(1.0, aw.ConvertUtil.point_to_inch(72))

# Add content to demonstrate the new margins.
builder.writeln(
    f"This Text is {page_setup.left_margin} points/{aw.ConvertUtil.point_to_inch(page_setup.left_margin)} inches from the left, " +
    f"{page_setup.right_margin} points/{aw.ConvertUtil.point_to_inch(page_setup.right_margin)} inches from the right, " +
    f"{page_setup.top_margin} points/{aw.ConvertUtil.point_to_inch(page_setup.top_margin)} inches from the top, " +
    f"and {page_setup.bottom_margin} points/{aw.ConvertUtil.point_to_inch(page_setup.bottom_margin)} inches from the bottom of the page.")

doc.save(ARTIFACTS_DIR + "UtilityClasses.points_and_inches.docx")
```

### See Also

* module [aspose.words](../../)
* class [ConvertUtil](../)

