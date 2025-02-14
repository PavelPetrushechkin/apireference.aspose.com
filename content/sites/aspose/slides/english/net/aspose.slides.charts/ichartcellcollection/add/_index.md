---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: Add new cell to the collection.
type: docs
weight: 40
url: /net/aspose.slides.charts/ichartcellcollection/add/
---
## Add(IChartDataCell) {#add}

Add new cell to the collection.

```csharp
public void Add(IChartDataCell chartDataCell)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | IChartDataCell | New cell to add. |

### See Also

* interface [IChartDataCell](../../ichartdatacell)
* interface [IChartCellCollection](../../ichartcellcollection)
* namespace [Aspose.Slides.Charts](../../ichartcellcollection)
* assembly [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Creates [`IChartDataCell`](../../ichartdatacell) from specified value and adds it to the collection.

```csharp
public void Add(object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | Object | The value. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | if limit exceeded |

### Remarks

This method adds worksheet with name AUTO_DATA and adds all values there. If you use [`IChartDataWorkbook`](../../ichartdataworkbook) to add or edit Cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680

### See Also

* interface [IChartCellCollection](../../ichartcellcollection)
* namespace [Aspose.Slides.Charts](../../ichartcellcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
