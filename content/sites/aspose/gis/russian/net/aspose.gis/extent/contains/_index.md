---
title: Contains
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет содержит ли этот экстент координату определенную аргументами.
type: docs
weight: 120
url: /ru/net/aspose.gis/extent/contains/
---
## Contains(double, double) {#contains_2}

Определяет, содержит ли этот экстент координату, определенную аргументами.

```csharp
public bool Contains(double x, double y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | X координаты. |
| y | Double | Y координаты. |

### Возвращаемое значение

Значение, указывающее, находится ли координата внутри ограничивающей рамки.

### Примечания

Координаты, расположенные на границах этого[`Extent`](../../extent) are считается содержащимся в этом[`Extent`](../../extent) .

### Смотрите также

* class [Extent](../../extent)
* пространство имен [Aspose.Gis](../../extent)
* сборка [Aspose.GIS](../../../)

---

## Contains(Extent) {#contains}

Определяет, содержит ли этот экстент аргумент.

```csharp
public bool Contains(Extent extent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extent | Extent | Другая степень. |

### Возвращаемое значение

Значение, указывающее, содержит ли этот экстент аргумент.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент`null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) в этой степени и аргумент оба не`null` и не равны друг другу. |

### Примечания

Координаты, расположенные на границах этого[`Extent`](../../extent) are считается содержащимся в этом[`Extent`](../../extent) . По этой причине считается, что равные экстенты содержат друг друга.

### Смотрите также

* class [Extent](../../extent)
* пространство имен [Aspose.Gis](../../extent)
* сборка [Aspose.GIS](../../../)

---

## Contains(IGeometry) {#contains_1}

Определяет, содержит ли этот экстент аргумент.

```csharp
public bool Contains(IGeometry geometry)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometry | IGeometry | Геометрия для проверки на сдерживание. |

### Возвращаемое значение

Значение, указывающее, содержит ли этот экстент аргумент.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент`null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) в этой степени и аргумент оба не`null` и не равны друг другу. |

### Примечания

Координаты, расположенные на границах этого[`Extent`](../../extent) are считается содержащимся в этом[`Extent`](../../extent) .

### Смотрите также

* interface [IGeometry](../../../aspose.gis.geometries/igeometry)
* class [Extent](../../extent)
* пространство имен [Aspose.Gis](../../extent)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
