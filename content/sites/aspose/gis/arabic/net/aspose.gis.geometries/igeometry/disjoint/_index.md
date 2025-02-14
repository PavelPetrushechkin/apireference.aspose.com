---
title: Disjoint
second_title: Aspose.GIS لمرجع .NET API
description: لتحديد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.
type: docs
weight: 180
url: /ar/net/aspose.gis.geometries/igeometry/disjoint/
---
## IGeometry.Disjoint method

لتحديد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.

```csharp
public bool Disjoint(IGeometry other)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| other | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "منفصلة مكانيًا" عن هندسة أخرى.`false` خلاف ذلك.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الحجة`null`. |
| ArgumentException | إحدى الأشكال الهندسية غير صالحة بحيث لا يمكن إنهاء العملية . |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) من الأشكال الهندسية غير متكافئة . يمكنك استخدام[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) من أجل تحويل الأشكال الهندسية إلى نفس النظام المرجعي spatial . |

### ملاحظات

تختبر هذه الطريقة ما إذا كانت الأشكال الهندسية مفككة من حيث مصفوفة تقاطع DE-9IM . بشكل أساسي ، تختبر عدم وجود نقاط مشتركة بين شكلين هندسيين. هذه الطريقة تعادل: راجع مواصفات ميزات OpenGIS البسيطة للحصول على مزيد من التفاصيل حول DE-9IM.

```csharp
this.Relate(other, "FF*FF****");
```

### أنظر أيضا

* method [Intersects](../intersects)
* interface [IGeometry](../../igeometry)
* مساحة الاسم [Aspose.Gis.Geometries](../../igeometry)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
