---
title: SqlServerOptions
second_title: Справочник по Aspose.GIS for .NET API
description: Параметры драйвера для формата SqlServer. На данный момент драйвер не предоставляет настраиваемых параметров.
type: docs
weight: 620
url: /ru/net/aspose.gis.formats.sqlserver/sqlserveroptions/
---
## SqlServerOptions class

Параметры драйвера для формата SqlServer. На данный момент драйвер не предоставляет настраиваемых параметров.

```csharp
public class SqlServerOptions : DatabaseDriverOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SqlServerOptions](sqlserveroptions)() | Создать новый экземпляр. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | Определяет, закрывается ли незакрытыйLinearRing в каждой геометрии. По умолчанию`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | Определяет, добавлять ли новую точку посередине к каждому сегменту геометрии. По умолчанию`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | Определяет, удалять ли ближайшие точки в каждой геометрии. По умолчанию`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | Определяет расстояние для[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints) . По умолчанию`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | Допуск, используемый для линеаризации геометрии кривой. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | А[`PrecisionModel`](../../aspose.gis/precisionmodel) который будет применен к координате M при добавлении геометрий в[`VectorLayer`](../../aspose.gis/vectorlayer) или когда они читаются из[`VectorLayer`](../../aspose.gis/vectorlayer) . Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | Определяет, удаляются ли точки, лежащие на одном и том же сегменте в каждой геометрии. По умолчанию`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | Определяет расстояние для[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments) . По умолчанию`0` . |
| [SpatialReferenceSystemMode](../../aspose.gis/databasedriveroptions/spatialreferencesystemmode) { get; set; } | Определяет, как следует обрабатывать SRS неизвестных геометрий для базы данных при их добавлении в слой. Значение по умолчанию:ThrowException . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | Определяет, следует ли проверять геометрию при добавлении в слой. Если установлено значение`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)вызывается для геометрии each , когда она добавляется к слою, и если проверка не пройдена ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid) является`false` ),[`GisException`](../../aspose.gis/gisexception) брошен. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | Определяет, разрешено ли преобразование полигона или мультиполигона в линию. По умолчанию`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | А[`PrecisionModel`](../../aspose.gis/precisionmodel)который будет применяться к координатам X и Y при добавлении геометрии в[`VectorLayer`](../../aspose.gis/vectorlayer) или когда они читаются из[`VectorLayer`](../../aspose.gis/vectorlayer) . Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | А[`PrecisionModel`](../../aspose.gis/precisionmodel) который будет применен к координате Z при добавлении геометрии в[`VectorLayer`](../../aspose.gis/vectorlayer) или когда они читаются из[`VectorLayer`](../../aspose.gis/vectorlayer) . Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact) . |

### Смотрите также

* class [DatabaseDriverOptions](../../aspose.gis/databasedriveroptions)
* пространство имен [Aspose.Gis.Formats.SqlServer](../../aspose.gis.formats.sqlserver)
* сборка [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
