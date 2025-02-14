---
title: NewValueSpecifiedUnits
second_title: Справочник по Aspose.SVG для .NET API
description: Сбросить значение как число с соответствующим unitType тем самым заменив значения для всех атрибутов объекта.
type: docs
weight: 60
url: /ru/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Сбросить значение как число с соответствующим unitType, тем самым заменив значения для всех атрибутов объекта.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newUnitType | UInt16 | Тип единицы измерения для значения (например, SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Значение угла. |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | код[`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err) Возникает, если unitType имеет значение SVG_ANGLETYPE_UNKNOWN или не является допустимой константой типа единицы измерения (одной из других констант SVG_ANGLETYPE_*, определенных в этом интерфейсе). |
| [DOMException](../../../aspose.svg.dom/domexception) | код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err) Возникает, когда угол соответствует атрибуту только для чтения или когда сам объект доступен только для чтения. |

### Смотрите также

* class [SVGAngle](../../svgangle)
* пространство имен [Aspose.Svg.DataTypes](../../svgangle)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
