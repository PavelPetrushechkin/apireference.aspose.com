---
title: GetValuesList
second_title: Aspose.GIS لمرجع .NET API
description: الحصول على قيم تسلسل السمات كقائمة.
type: docs
weight: 70
url: /ar/net/aspose.gis/feature/getvalueslist/
---
## Feature.GetValuesList&lt;T&gt; method

الحصول على قيم تسلسل السمات كقائمة.

```csharp
public List<T> GetValuesList<T>(string attributeName, string separator)
```

| معامل | وصف |
| --- | --- |
| T | النوع المطلوب للقيم. |
| attributeName | اسم السمة. |
| separator | سلسلة تُستخدم لفصل اسم السمة وقيمة الفهرس للتسلسل. |

### قيمة الإرجاع

قائمة قيم السمات التي تسمي مختلفة حسب قيمة فهرس التسلسل.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | اسم السمة هو`null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مؤمنة. |
| InvalidOperationException | لم يتم تعيين قيمة هذه السمة لهذه الميزة. |
| InvalidCastException | النوع المطلوب لا يتم تنفيذهIConvertible. |
| InvalidCastException | قيمة السمة هي`null`، ولكن النوع المطلوب هو نوع القيمة. |
| FormatException | فشل التحويل لأن القيمة بتنسيق غير صحيح. |
| OverflowException | فشل التحويل بسبب تجاوز السعة. |

### ملاحظات

هذا يستخدم[`GetValue`](../getvalue) للحصول على قيمة واحدة. لذلك ، تقوم هذه الطريقة بتحويل القيمة تلقائيًا إلى النوع المطلوب في معلمة النوع العام. إذا لم يتم العثور على السمة بالفهرس 0 ، فسيتم إنشاؤهاArgumentException .

### أنظر أيضا

* class [Feature](../../feature)
* مساحة الاسم [Aspose.Gis](../../feature)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
