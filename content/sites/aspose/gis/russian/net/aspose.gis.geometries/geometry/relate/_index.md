---
title: Relate
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет соответствует ли матрица пересечения DE9IM этой геометрии и указанной геометрии предоставленному шаблону.
type: docs
weight: 300
url: /ru/net/aspose.gis.geometries/geometry/relate/
---
## Geometry.Relate method

Определяет, соответствует ли матрица пересечения DE-9IM этой геометрии и указанной геометрии предоставленному шаблону.

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия. |
| intersectionPatternMatrix | String | Шаблон для сопоставления. Это должна быть строка длиной, равной 9. Каждый символ строки представляет ожидаемый размер пересечения: символ 0 - между внутренностями геометрий.символ 1 - между внутренней частью этой геометрии и границей другой геометрии.символ 2 - между внутренней частью этой геометрии и внешней частью другой геометрии.символ 3 - между границей этой геометрии и внутренней частью другой геометрии.символ 4 - между границами геометрий.символ 5 - между границей этой геометрии и экстерьером другой геометрии.символ 6 - между экстерьером этой геометрии и внутренностью другой геометрии.символ 7 - между экстерьером этой геометрии и границей другой геометрии.символ 8 - между экстерьерами геометрий. Возможные значения каждого символа: * - любое значение;F - нет пересечения;Т - любой перекресток;0 - точка пересечения (например, общая точка);1 - пересечение линий (например, общий отрезок линии);2 - пересечение областей (например, общая часть полигона); Например, шаблон пересечения "F0*******" означает, что не должно быть пересечения между геометриями inners , а пересечение границ геометрий должно быть точкой. узор. |

### Возвращаемое значение

`true` если эта матрица пересечения соответствует шаблону;`false` иначе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *other* является`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) для преобразования геометрии в одну и ту же систему отсчета пространственного . |

### Примечания

Этот метод строит матрицу пересечений DE-9IM и сопоставляет ее с шаблоном Дополнительные сведения о матрице пересечений DE-9IM см. в Спецификации простых функций OpenGIS.

### Примеры

Следующий код:  определит, равны ли геометрии в пространстве.

```csharp
geometry.Relate(other, "T*F**FFF*");
```

### Смотрите также

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* пространство имен [Aspose.Gis.Geometries](../../geometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
