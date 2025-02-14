---
title: Convert
second_title: Aspose.GIS لمرجع .NET API
description: تحويل طبقة إلى تنسيق مختلف .
type: docs
weight: 180
url: /ar/net/aspose.gis/vectorlayer/convert/
---
## Convert(string, FileDriver, string, FileDriver) {#convert_2}

تحويل طبقة إلى تنسيق مختلف .

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | محرك التنسيق للطبقة المصدر. |
| destinationPath | String | المسار إلى الطبقة التي سيتم إنشاؤها نتيجة للتحويل. |
| destinationDriver | FileDriver | محرك التنسيق للطبقة الوجهة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | كلا المسارين هو`null`. |

### أنظر أيضا

* class [FileDriver](../../filedriver)
* class [VectorLayer](../../vectorlayer)
* مساحة الاسم [Aspose.Gis](../../vectorlayer)
* المجسم [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver) {#convert}

تحويل طبقة إلى تنسيق مختلف .

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | AbstractPath | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | محرك التنسيق للطبقة المصدر. |
| destinationPath | AbstractPath | المسار إلى الطبقة التي سيتم إنشاؤها نتيجة للتحويل. |
| destinationDriver | FileDriver | محرك التنسيق للطبقة الوجهة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | كلا المسارين هو`null`. |

### أنظر أيضا

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [VectorLayer](../../vectorlayer)
* مساحة الاسم [Aspose.Gis](../../vectorlayer)
* المجسم [Aspose.GIS](../../../)

---

## Convert(string, FileDriver, string, FileDriver, ConversionOptions) {#convert_3}

تحويل طبقة إلى تنسيق مختلف .

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver, ConversionOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | محرك التنسيق للطبقة المصدر. |
| destinationPath | String | المسار إلى الطبقة التي سيتم إنشاؤها نتيجة للتحويل. |
| destinationDriver | FileDriver | محرك التنسيق للطبقة الوجهة. |
| options | ConversionOptions | خيارات لإجراء التحويل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | كلا المسارين هو`null`. |
| ArgumentException | كائن الخيارات له نوع غير صحيح لبرنامج التشغيل هذا. |
| [GisException](../../gisexception) | خطأ في قراءة أو كتابة الميزة إلى / من الملف. |
| IOException | حدث خطأ في الإدخال / الإخراج. |
| NotSupportedException | نظام الإسناد المكاني المحدد في*options*لا يدعمه*destinationDriver* . |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | فشل تحويل هندسة المعالم من نظام الإسناد المكاني المصدر إلى نظام الإسناد المكاني المستهدف. |

### أنظر أيضا

* class [FileDriver](../../filedriver)
* class [ConversionOptions](../../conversionoptions)
* class [VectorLayer](../../vectorlayer)
* مساحة الاسم [Aspose.Gis](../../vectorlayer)
* المجسم [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver, ConversionOptions) {#convert_1}

تحويل طبقة إلى تنسيق مختلف .

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver, ConversionOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | AbstractPath | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | محرك التنسيق للطبقة المصدر. |
| destinationPath | AbstractPath | المسار إلى الطبقة التي سيتم إنشاؤها نتيجة للتحويل. |
| destinationDriver | FileDriver | محرك التنسيق للطبقة الوجهة. |
| options | ConversionOptions | خيارات لإجراء التحويل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | كلا المسارين هو`null`. |
| ArgumentException | كائن الخيارات له نوع غير صحيح لبرنامج التشغيل هذا. |
| [GisException](../../gisexception) | خطأ في قراءة أو كتابة الميزة إلى / من الملف. |
| IOException | حدث خطأ في الإدخال / الإخراج. |
| NotSupportedException | نظام الإسناد المكاني المحدد في*options*لا يدعمه*destinationDriver* . |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | فشل تحويل هندسة المعالم من نظام الإسناد المكاني المصدر إلى نظام الإسناد المكاني المستهدف. |

### أنظر أيضا

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [ConversionOptions](../../conversionoptions)
* class [VectorLayer](../../vectorlayer)
* مساحة الاسم [Aspose.Gis](../../vectorlayer)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
