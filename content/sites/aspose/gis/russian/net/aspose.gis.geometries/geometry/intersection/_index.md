---
title: Intersection
second_title: Справочник по Aspose.GIS for .NET API
description: Строит пересечение между этой геометрией и заданной геометрией.
type: docs
weight: 270
url: /ru/net/aspose.gis.geometries/geometry/intersection/
---
## Geometry.Intersection method

Строит пересечение между этой геометрией и заданной геометрией.

```csharp
public IGeometry Intersection(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия, с которой вычисляется пересечение. |

### Возвращаемое значение

Геометрия, представляющая пересечение этой геометрии и аргумента. Результирующая геометрия содержит набор точек , которые присутствуют как в этой геометрии, так и в аргументе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *other* является`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) для преобразования геометрии в одну и ту же систему отсчета пространственного . |

### Смотрите также

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* пространство имен [Aspose.Gis.Geometries](../../geometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
