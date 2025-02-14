---
title: Within
second_title: Aspose.GIS لمرجع .NET API
description: لتحديد ما إذا كانت هذه الهندسة ضمن نطاق محدد.
type: docs
weight: 440
url: /ar/net/aspose.gis.geometries/geometry/within/
---
## Within(Extent) {#within}

لتحديد ما إذا كانت هذه الهندسة ضمن نطاق محدد.

```csharp
public bool Within(Extent extent)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| extent | Extent | المدى. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة ضمن المدى ؛`false` خلاف ذلك.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الحجة`null`. |

### أنظر أيضا

* method [Contains](../../../aspose.gis/extent/contains)
* class [Extent](../../../aspose.gis/extent)
* class [Geometry](../../geometry)
* مساحة الاسم [Aspose.Gis.Geometries](../../geometry)
* المجسم [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

لتحديد ما إذا كانت هذه الهندسة ضمن هندسة محددة.

```csharp
public bool Within(IGeometry other)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| other | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "مكانيًا ضمن" هندسة أخرى.`false` خلاف ذلك.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الحجة`null`. |
| ArgumentException | إحدى الأشكال الهندسية غير صالحة بحيث لا يمكن إنهاء العملية . |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) من الأشكال الهندسية غير متكافئة . يمكنك استخدام[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) من أجل تحويل الأشكال الهندسية إلى نفس النظام المرجعي spatial . |

### ملاحظات

تختبر هذه الطريقة ما إذا كانت إحدى الأشكال الهندسية ضمن أخرى من حيث مصفوفة تقاطع DE-9IM . توجد هندسة واحدة داخل أخرى ، إذا كانت هناك هندسة أخرى تحتوي على كل نقطة من الأشكال الهندسية والأشكال الهندسية تقاطع التصميمات الداخلية. هذه الطريقة تعادل: راجع مواصفات ميزات OpenGIS البسيطة للحصول على مزيد من التفاصيل حول DE-9IM وعلاقة "مكانيًا داخل".

```csharp
this.Relate(other, "T*F**F***");
```

### أنظر أيضا

* method [SpatiallyContains](../../igeometry/spatiallycontains)
* method [CoveredBy](../../igeometry/coveredby)
* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* مساحة الاسم [Aspose.Gis.Geometries](../../geometry)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
