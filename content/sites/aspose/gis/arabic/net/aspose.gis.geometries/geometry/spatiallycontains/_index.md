---
title: SpatiallyContains
second_title: Aspose.GIS لمرجع .NET API
description: لتحديد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة.
type: docs
weight: 360
url: /ar/net/aspose.gis.geometries/geometry/spatiallycontains/
---
## Geometry.SpatiallyContains method

لتحديد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة.

```csharp
public bool SpatiallyContains(IGeometry other)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| other | IGeometry | هندسة. |

### قيمة الإرجاع

`true`إذا كانت هذه الهندسة "تحتوي مكانيًا" على هندسة أخرى.`false` خلاف ذلك.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الحجة`null`. |
| ArgumentException | إحدى الأشكال الهندسية غير صالحة بحيث لا يمكن إنهاء العملية . |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) من الأشكال الهندسية غير متكافئة . يمكنك استخدام[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) من أجل تحويل الأشكال الهندسية إلى نفس النظام المرجعي spatial . |

### ملاحظات

تختبر هذه الطريقة ما إذا كانت إحدى الأشكال الهندسية تحتوي على أخرى من حيث مصفوفة تقاطع DE-9IM. هذه الطريقة تعادل:

```csharp
other.Within(this);
```

### أنظر أيضا

* method [Within](../../igeometry/within)
* method [Covers](../../igeometry/covers)
* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* مساحة الاسم [Aspose.Gis.Geometries](../../geometry)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
