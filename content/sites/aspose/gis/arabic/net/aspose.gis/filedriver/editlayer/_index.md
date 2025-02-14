---
title: EditLayer
second_title: Aspose.GIS لمرجع .NET API
description: يفتح طبقة للتحرير .
type: docs
weight: 70
url: /ar/net/aspose.gis/filedriver/editlayer/
---
## EditLayer(string, DriverOptions) {#editlayer_1}

يفتح طبقة للتحرير .

```csharp
public VectorLayer EditLayer(string path, DriverOptions options = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار الملف. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال على[`VectorLayer`](../../vectorlayer).

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | كائن الخيارات له نوع غير صحيح لبرنامج التشغيل هذا. |
| ArgumentNullException | الطريق`null`. |
| [GisException](../../gisexception) | خطأ في قراءة الميزة من الملف. |
| IOException | حدث خطأ في الإدخال / الإخراج. |

### أنظر أيضا

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [FileDriver](../../filedriver)
* مساحة الاسم [Aspose.Gis](../../filedriver)
* المجسم [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, DriverOptions) {#editlayer}

يفتح طبقة للتحرير .

```csharp
public virtual VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | AbstractPath | مسار الملف. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال على[`VectorLayer`](../../vectorlayer).

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | كائن الخيارات له نوع غير صحيح لبرنامج التشغيل هذا. |
| ArgumentNullException | الطريق`null`. |
| [GisException](../../gisexception) | خطأ في قراءة الميزة من الملف. |
| NotSupportedException | لا يمكن للسائق تعديل الطبقات. |
| IOException | حدث خطأ في الإدخال / الإخراج. |

### ملاحظات

يقوم السائق بإنشاء طبقة داخلية بكل الميزات. ولكن لدينا خيار استخدام مساحة القرص بدلاً من ذاكرة الوصول العشوائي . هناك برامج تشغيل لمزيد من الاستخدام الأمثل للموارد (انظر وثائق برنامج التشغيل المحدد) . كما يمكن للسائق تحرير طبقة إذا كان بإمكانه إنشاء الطبقات وفتحها.

### أنظر أيضا

* class [VectorLayer](../../vectorlayer)
* class [AbstractPath](../../abstractpath)
* class [DriverOptions](../../driveroptions)
* class [FileDriver](../../filedriver)
* مساحة الاسم [Aspose.Gis](../../filedriver)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
