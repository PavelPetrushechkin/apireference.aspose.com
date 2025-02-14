---
title: CreateLocal
second_title: Aspose.GIS for .NET API Referansı
description: Yerel SRS oluşturun.
type: docs
weight: 370
url: /tr/net/aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/
---
## SpatialReferenceSystem.CreateLocal method

Yerel SRS oluşturun.

```csharp
public static LocalSpatialReferenceSystem CreateLocal(string name, LocalDatum datum, Unit unit, 
    ICollection<Axis> axises, Identifier identifier = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | SRS'nin adı. |
| datum | LocalDatum | SRS'de kullanılacak veriler. |
| unit | Unit | SRS'de kullanılacak birim. |
| axises | ICollection`1 | SRS'de kullanılacak eksenler. Boş olmamalı |
| identifier | Identifier | SRS'ye eklenecek olan tanımlayıcı. Bir Tanımlayıcı eklemek diğer SRS parametrelerini değiştirmeyecektir. Tanımlayıcı ve SRS parametrelerinin tutarlılığını sağlamak size kalmıştır. |

### Geri dönüş değeri

Yeni Yerel SRS.

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | *axises* boş. |
| ArgumentNullException | dışında herhangi bir argüman*identifier* boş. |

### Ayrıca bakınız

* class [LocalSpatialReferenceSystem](../../localspatialreferencesystem)
* class [LocalDatum](../../localdatum)
* class [Unit](../../unit)
* class [Axis](../../axis)
* class [Identifier](../../identifier)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* ad alanı [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
