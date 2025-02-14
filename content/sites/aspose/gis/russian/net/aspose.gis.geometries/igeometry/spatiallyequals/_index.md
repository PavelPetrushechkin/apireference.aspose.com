---
title: SpatiallyEquals
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет является ли эта геометрия пространственно равной указанной геометрии.
type: docs
weight: 320
url: /ru/net/aspose.gis.geometries/igeometry/spatiallyequals/
---
## IGeometry.SpatiallyEquals method

Определяет, является ли эта геометрия пространственно равной указанной геометрии.

```csharp
public bool SpatiallyEquals(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия. |

### Возвращаемое значение

`true` если эта геометрия "пространственно равна" указанной геометрии.`false` иначе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) для преобразования геометрии в одну и ту же систему отсчета пространственного . |

### Примечания

Этот метод проверяет равенство с точки зрения матрицы пересечения DE-9IM. Это не зависит от порядка компонентов (например, порядка внутренних колец в многоугольнике), значений Z и M. По сути, он проверяет , что две геометрии занимают одно и то же «пространство» при проецировании на двумерное пространство. Этот метод эквивалентен: Дополнительные сведения о DE-9IM см. в Спецификации простых функций OpenGIS.

```csharp
this.Relate(other, "T*F**FFF*");
```

### Смотрите также

* interface [IGeometry](../../igeometry)
* пространство имен [Aspose.Gis.Geometries](../../igeometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
