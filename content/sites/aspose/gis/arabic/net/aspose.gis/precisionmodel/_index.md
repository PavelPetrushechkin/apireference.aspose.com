---
title: PrecisionModel
second_title: Aspose.GIS لمرجع .NET API
description: PrecisionModel./precisionmodel يحدد عددًا من الأرقام المهمة في إحداثي.
type: docs
weight: 1210
url: /ar/net/aspose.gis/precisionmodel/
---
## PrecisionModel class

[`PrecisionModel`](../precisionmodel) يحدد عددًا من الأرقام المهمة في إحداثي.

```csharp
public abstract class PrecisionModel : IEquatable<PrecisionModel>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Exact](../../aspose.gis/precisionmodel/exact) { get; } | إرجاع نموذج الدقة الدقيق. وفقًا لنموذج الدقة الدقيق ، تكون جميع الأرقام في القيمة المزدوجة مهمة . |
| [IsExact](../../aspose.gis/precisionmodel/isexact) { get; } | الحصول على قيمة تشير إلى ما إذا كان نموذج الدقة هذا دقيقًا. |
| [IsRounding](../../aspose.gis/precisionmodel/isrounding) { get; } | الحصول على قيمة تشير إلى ما إذا كان نموذج الدقة هذا يتم تقريبه. |
| abstract [SignificantDigits](../../aspose.gis/precisionmodel/significantdigits) { get; } | الحصول على عدد من الأرقام المعنوية في نموذج الدقة إذا كان يتم التقريب . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Rounding](../../aspose.gis/precisionmodel/rounding)(int) | إرجاع نموذج دقة التقريب . وفقًا لنموذج التقريب الدقيق ، يكون عدد الأرقام محدودًا فقط . |
| override [Equals](../../aspose.gis/precisionmodel/equals#equals_1)(object) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [Equals](../../aspose.gis/precisionmodel/equals#equals)(PrecisionModel) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| override [GetHashCode](../../aspose.gis/precisionmodel/gethashcode)() | بمثابة وظيفة التجزئة الافتراضية. |
| [operator ==](../../aspose.gis/precisionmodel/op_equality) | تنفيذ عامل التشغيل == . |
| [operator !=](../../aspose.gis/precisionmodel/op_inequality) | تنفذ عامل التشغيل! = . |

### ملاحظات

هناك نوعان من طراز PrecisionModel:  بالضبط[`PrecisionModel`](../precisionmodel) (جميع الأرقام مهمة) ؛ مدور[`PrecisionModel`](../precisionmodel) (بعض الأرقام ذات دلالة). أ[`PrecisionModel`](../precisionmodel) يمكن ضبطها على[`VectorLayer`](../vectorlayer) عبر[`DriverOptions`](../driveroptions) لتقريب الإحداثيات عند كتابة أو قراءة الأشكال الهندسية.

### أنظر أيضا

* property [XYPrecisionModel](../driveroptions/xyprecisionmodel)
* property [ZPrecisionModel](../driveroptions/zprecisionmodel)
* property [MPrecisionModel](../driveroptions/mprecisionmodel)
* مساحة الاسم [Aspose.Gis](../../aspose.gis)
* المجسم [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
