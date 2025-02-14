---
title: Validate
second_title: Справочник по Aspose.GIS for .NET API
description: Определите действительна ли эта SRS.
type: docs
weight: 240
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystem/validate/
---
## SpatialReferenceSystem.Validate method

Определите, действительна ли эта SRS.

```csharp
public abstract bool Validate(out string errorMessage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| errorMessage | String& | Если метод возвращает`false` то это описание недействительности. |

### Возвращаемое значение

`true` если SRS действителен,`false` в противном случае.

### Примечания

Действительная SRS должна иметь действительный эллипсоид. - Географическая SRS должна иметь ровно одну ось Восток/Запад, ровно одну ось Север/Юг и необязательную ось Вверх/Вниз вертикальная SRS). — Проецируемая SRS должна иметь ровно одну ось Восток/Запад, ровно одну ось Север/Юг и необязательную ось Up/Down (необязательная ось присутствует, когда проецируемая SRS представляет собой соединение двухмерной географической SRS и вертикальной SRS). — Геоцентрическая SRS должна иметь ровно одну ось Восток/Запад, ровно одну ось Север/Юг и ровно одну ось Other. — Вертикальная SRS должна иметь ровно одну ось Up/Down. — Локальная SRS должна иметь хотя бы одну ось. Направления осей не измеряются. — составной SRS должен быть комбинацией действительных географических/проекционных и действительных вертикальных SRS.

### Смотрите также

* class [SpatialReferenceSystem](../../spatialreferencesystem)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
