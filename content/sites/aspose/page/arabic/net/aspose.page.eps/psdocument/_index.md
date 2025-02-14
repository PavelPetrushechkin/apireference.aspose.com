---
title: PsDocument
second_title: Aspose.Page لمرجع NET API
description: تحتوي هذه الفئة على مستندات PS / EPS .
type: docs
weight: 100
url: /ar/net/aspose.page.eps/psdocument/
---
## PsDocument class

تحتوي هذه الفئة على مستندات PS / EPS .

```csharp
public sealed class PsDocument : Document
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PsDocument](psdocument)(Stream) | يتم التهيئة[`PsDocument`](../psdocument) مع دفق ملف PS / EPS . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [NumberOfPages](../../aspose.page.eps/psdocument/numberofpages) { get; } | إرجاع عدد الصفحات في مستند PDF الناتج. |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetXmpMetadata](../../aspose.page.eps/psdocument/getxmpmetadata)() | يقرأ ملف PS / EPS ويستخرج XmpMetdata إذا كان موجودًا بالفعل أو قم بإضافة ملف جديد إذا لم يكن موجودًا. |
| [Merge](../../aspose.page.eps/psdocument/merge)(string[], Device, SaveOptions) | يدمج ملفات PS / EPS بجهاز. |
| [Save](../../aspose.page.eps/psdocument/save#save_1)(Stream) | حفظ معين[`PsDocument`](../psdocument) كملف EPS. يتم استخدام هذه الطريقة فقط بعد تحديث بيانات تعريف XMP . تقوم بحفظ ملف EPS الأولي ببيانات وصفية حالية محدثة أو ملف جديد تم إنشاؤه أثناء استدعاء طريقة GetMetadata . في الحالة الأخيرة ، تتم إضافة جميع كود PostScript الضروري وتعليقات EPS. |
| override [Save](../../aspose.page.eps/psdocument/save#save)(Device, SaveOptions) | يحفظ ملف PS / EPS على الجهاز. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps)(Bitmap, Stream, PsSaveOptions) | حفظ كائن الصورة النقطية في تدفق إخراج EPS . |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_1)(Bitmap, string, PsSaveOptions) | حفظ كائن الصورة النقطية في ملف EPS . |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_2)(Stream, Stream, PsSaveOptions) | يحفظ صورة PNG / JPEG / TIFF / BMP / GIF / EMF من دفق الإدخال إلى تدفق إخراج EPS. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_3)(string, string, PsSaveOptions) | يحفظ صورة PNG / JPEG / TIFF / BMP / GIF / EMF من ملف إلى ملف EPS. |

### أنظر أيضا

* class [Document](../../aspose.page/document)
* مساحة الاسم [Aspose.Page.EPS](../../aspose.page.eps)
* المجسم [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
