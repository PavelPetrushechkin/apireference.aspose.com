---
title: CsvOptions
second_title: Aspose.GIS for .NET API 参考
description: CSV 格式的驱动程序特定选项
type: docs
weight: 190
url: /zh/net/aspose.gis.formats.csv/csvoptions/
---
## CsvOptions class

CSV 格式的驱动程序特定选项。

```csharp
public class CsvOptions : DriverOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [CsvOptions](csvoptions)() | 创建新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | 确定是否关闭未关闭的LinearRing在每个几何中。默认为`false`. |
| [ColumnM](../../aspose.gis.formats.csv/csvoptions/columnm) { get; set; } | 获取或设置包含 M 坐标值的列名。 默认为`null`. |
| [ColumnWkt](../../aspose.gis.formats.csv/csvoptions/columnwkt) { get; set; } | 获取或设置列的名称，其中包含用于表示几何的众所周知的文本。 默认为`null`. |
| [ColumnX](../../aspose.gis.formats.csv/csvoptions/columnx) { get; set; } | 获取或设置包含 X 坐标值的列名。 默认为`null`. |
| [ColumnY](../../aspose.gis.formats.csv/csvoptions/columny) { get; set; } | 获取或设置包含 Y 坐标值的列名。 默认为`null`. |
| [ColumnZ](../../aspose.gis.formats.csv/csvoptions/columnz) { get; set; } | 获取或设置包含 Z 坐标值的列名。 默认为`null`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | 确定是否在每个几何段的中间添加一个新点。默认为`false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | 确定是否删除每个几何图形中的近点。默认为`false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | 确定距离[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints).默认为`0`. |
| [Delimiter](../../aspose.gis.formats.csv/csvoptions/delimiter) { get; set; } | 获取或设置用作分隔值的分隔符的字符。 默认为','。 |
| [DoubleQuoteEscape](../../aspose.gis.formats.csv/csvoptions/doublequoteescape) { get; set; } | 获取或设置用作双引号的转义字母的字符。 默认为'"'。 |
| [HasAttributeNames](../../aspose.gis.formats.csv/csvoptions/hasattributenames) { get; set; } | 确定是否存在具有属性名称的标题行。 默认为`true`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | 用于线性化曲线几何形状的公差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | 一个[`PrecisionModel`](../../aspose.gis/precisionmodel)将几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或者当它们从[`VectorLayer`](../../aspose.gis/vectorlayer). 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact). |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | 确定是否删除位于每个几何图形中同一段上的点。默认为`false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | 确定距离[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments).默认为`0`. |
| [StartLineNumber](../../aspose.gis.formats.csv/csvoptions/startlinenumber) { get; set; } | 获取或设置从零开始的行数，在读取数据时将首先显示。 默认为 0。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | 确定在将几何图形添加到图层时是否应对其进行验证。 如果设置为`true`,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)在将 each 几何图形添加到图层时以及如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)是`false`),[`GisException`](../../aspose.gis/gisexception)被抛出。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认为`false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | 一个[`PrecisionModel`](../../aspose.gis/precisionmodel)将几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或者当它们从[`VectorLayer`](../../aspose.gis/vectorlayer). 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | 一个[`PrecisionModel`](../../aspose.gis/precisionmodel)当几何图形添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或者当它们从[`VectorLayer`](../../aspose.gis/vectorlayer). 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact). |

### 也可以看看

* class [DriverOptions](../../aspose.gis/driveroptions)
* 命名空间 [Aspose.Gis.Formats.Csv](../../aspose.gis.formats.csv)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
