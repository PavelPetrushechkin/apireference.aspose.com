---
title: OpenLayer
second_title: Aspose.GIS لمرجع .NET API
description: لفتح الطبقة ذات الاسم المحدد للقراءة.
type: docs
weight: 110
url: /ar/net/aspose.gis/dataset/openlayer/
---
## Dataset.OpenLayer method

لفتح الطبقة ذات الاسم المحدد للقراءة.

```csharp
public abstract VectorLayer OpenLayer(string name, DriverOptions options = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| name | String | اسم الطبقة المراد فتحها. |
| options | DriverOptions | افتح الخيارات. |

### قيمة الإرجاع

تم فتح الطبقة للقراءة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | الطبقة ذات الاسم المحدد غير موجودة ؛ كائن الخيارات له نوع غير صحيح لمجموعة البيانات هذه. |
| ArgumentException | كائن الخيارات له نوع غير صحيح لمجموعة البيانات هذه. |
| ArgumentNullException | الاسم هو`null`. |
| [GisException](../../gisexception) | خطأ في قراءة المعالم من الطبقة. |
| IOException | حدث خطأ في الإدخال / الإخراج. |

### أنظر أيضا

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [Dataset](../../dataset)
* مساحة الاسم [Aspose.Gis](../../dataset)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
