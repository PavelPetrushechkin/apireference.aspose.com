---
title: TickLabelAlignment
second_title: Aspose.Words for .NET API Reference
description: Gets or sets text alignment of axis tick labels.
type: docs
weight: 200
url: /net/aspose.words.drawing.charts/chartaxis/ticklabelalignment/
---
## ChartAxis.TickLabelAlignment property

Gets or sets text alignment of axis tick labels.

```csharp
public ParagraphAlignment TickLabelAlignment { get; set; }
```

## Remarks

This property has effect only for multi-line labels.

Default value is Center.

.

## Examples

Shows how to manipulate the tick marks and displayed values of a chart axis.

```csharp
Document doc = new Document();
DocumentBuilder builder = new DocumentBuilder(doc);

Shape shape = builder.InsertChart(ChartType.Scatter, 450, 250);
Chart chart = shape.Chart;

Assert.AreEqual(1, chart.Series.Count);
Assert.AreEqual("Y-Values", chart.Series[0].Name);

// Set the minor tick marks of the Y-axis to point away from the plot area,
// and the major tick marks to cross the axis.
ChartAxis axis = chart.AxisY;
axis.MajorTickMark = AxisTickMark.Cross;
axis.MinorTickMark = AxisTickMark.Outside;

// Set they Y-axis to show a major tick every 10 units, and a minor tick every 1 unit.
axis.MajorUnit = 10;
axis.MinorUnit = 1;

// Set the Y-axis bounds to -10 and 20.
// This Y-axis will now display 4 major tick marks and 27 minor tick marks.
axis.Scaling.Minimum = new AxisBound(-10);
axis.Scaling.Maximum = new AxisBound(20);

// For the X-axis, set the major tick marks at every 10 units,
// every minor tick mark at 2.5 units.
axis = chart.AxisX;
axis.MajorUnit = 10;
axis.MinorUnit = 2.5;

// Configure both types of tick marks to appear inside the graph plot area.
axis.MajorTickMark = AxisTickMark.Inside;
axis.MinorTickMark = AxisTickMark.Inside;

// Set the X-axis bounds so that the X-axis spans 5 major tick marks and 12 minor tick marks.
axis.Scaling.Minimum = new AxisBound(-10);
axis.Scaling.Maximum = new AxisBound(30);
axis.TickLabelAlignment = ParagraphAlignment.Right;

Assert.AreEqual(1, axis.TickLabelSpacing);

// Set the tick labels to display their value in millions.
axis.DisplayUnit.Unit = AxisBuiltInUnit.Millions;

// We can set a more specific value by which tick labels will display their values.
// This statement is equivalent to the one above.
axis.DisplayUnit.CustomUnit = 1000000;
doc.Save(ArtifactsDir + "Charts.AxisDisplayUnit.docx");
```

### See Also

* enum [ParagraphAlignment](../../../aspose.words/paragraphalignment)
* class [ChartAxis](../../chartaxis)
* namespace [Aspose.Words.Drawing.Charts](../../chartaxis)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
