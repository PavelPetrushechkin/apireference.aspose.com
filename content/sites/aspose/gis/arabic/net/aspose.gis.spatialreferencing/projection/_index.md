---
title: Projection
second_title: Aspose.GIS لمرجع .NET API
description: يمثل طريقة الإسقاط مع المعلمات التي تحول خط الطول وخط العرض إلى س  ص .
type: docs
weight: 2140
url: /ar/net/aspose.gis.spatialreferencing/projection/
---
## Projection class

يمثل طريقة الإسقاط مع المعلمات التي تحول (خط الطول وخط العرض) إلى (س ، ص) .

```csharp
public class Projection : IdentifiableObject
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AngularParametersUnit](../../aspose.gis.spatialreferencing/projection/angularparametersunit) { get; } | الوحدة المستخدمة للمعلمات الزاوية . |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode) { get; } | إذا كان معرف الكائنات هذا هو معرف EPSG - قم بإرجاع الكود الخاص به. خلاف ذلك - إرجاع -1 . |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier) { get; } | معرف هذا الكائن الذي يمكن التعرف عليه . |
| [LinearParametersUnit](../../aspose.gis.spatialreferencing/projection/linearparametersunit) { get; } | الوحدة المستخدمة للمعلمات الخطية . |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name) { get; } | اسم هذا الكائن . |
| [ParametersNames](../../aspose.gis.spatialreferencing/projection/parametersnames) { get; } | الحصول على مجموعة لا حصر لها من أسماء المعلمات المعطاة لهذا الإسقاط |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetParameterValue](../../aspose.gis.spatialreferencing/projection/getparametervalue)(string, ParameterType) | يحصل على معلمة بالاسم المحدد لهذا الإسقاط. |
| [IsEquivalent](../../aspose.gis.spatialreferencing/projection/isequivalent)(Projection) | المحددات هي إسقاطان متكافئان. خريطة الإسقاطات المكافئة (خطوط الطول والعرض) إلى (س ، ص) بالطريقة نفسها. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |
| [TryGetParameterValue](../../aspose.gis.spatialreferencing/projection/trygetparametervalue)(string, ParameterType) | يحصل على معلمة بالاسم المحدد لهذا الإسقاط. إذا لم يكن هناك مثل هذه المعلمة - العوائد`null` . |

### أنظر أيضا

* class [IdentifiableObject](../identifiableobject)
* مساحة الاسم [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* المجسم [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
