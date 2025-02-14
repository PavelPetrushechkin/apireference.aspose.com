---
title: Disjoint
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет не пересекается ли эта геометрия с указанной геометрией.
type: docs
weight: 180
url: /ru/net/aspose.gis.geometries/igeometry/disjoint/
---
## IGeometry.Disjoint method

Определяет, не пересекается ли эта геометрия с указанной геометрией.

```csharp
public bool Disjoint(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия. |

### Возвращаемое значение

`true` если эта геометрия «пространственно не пересекается» с другой геометрией.`false` иначе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) для преобразования геометрии в одну и ту же систему отсчета пространственного . |

### Примечания

Этот метод проверяет, не пересекаются ли геометрии с точки зрения матрицы пересечения DE-9IM. По сути, он проверяет, что две геометрии не имеют общих точек. Этот метод эквивалентен: Дополнительные сведения о DE-9IM см. в Спецификации простых функций OpenGIS.

```csharp
this.Relate(other, "FF*FF****");
```

### Смотрите также

* method [Intersects](../intersects)
* interface [IGeometry](../../igeometry)
* пространство имен [Aspose.Gis.Geometries](../../igeometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
