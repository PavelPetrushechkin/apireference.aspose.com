---
title: PsSaveOptions
second_title: Aspose.Page لمرجع NET API
description: تحتوي هذه الفئة على خيارات ضرورية لإدارة عملية تحويل المستند إلى ملف PostScript PS أو ملف Encapsulated PostScript EPS.
type: docs
weight: 80
url: /ar/net/aspose.page.eps.device/pssaveoptions/
---
## PsSaveOptions class

تحتوي هذه الفئة على خيارات ضرورية لإدارة عملية تحويل المستند إلى ملف PostScript (PS) أو ملف Encapsulated PostScript (EPS).

```csharp
public class PsSaveOptions : SaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PsSaveOptions](pssaveoptions#constructor)() | يقوم بتهيئة مثيل جديد لملف[`PsSaveOptions`](../pssaveoptions) فئة ذات القيم الافتراضية للأعلام!:SuppressErrors (صحيح) و!:Debug (خطأ) . |
| [PsSaveOptions](pssaveoptions#constructor_1)(bool) | يقوم بتهيئة مثيل جديد لملف[`PsSaveOptions`](../pssaveoptions) فئة مع القيم الافتراضية للعلم!:Debug (خطأ) . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AdditionalFontsFolders](../../aspose.page/saveoptions/additionalfontsfolders) { get; set; } | يحدد مجلدات إضافية حيث يجب أن يجد المحول الخطوط لمستند الإدخال. المجلد الافتراضي هو مجلد الخطوط القياسي حيث يجد نظام التشغيل الخطوط للاحتياجات الداخلية. |
| virtual [Debug](../../aspose.page/saveoptions/debug) { get; set; } | يحدد ما إذا كان يجب طباعة معلومات التصحيح إلى تدفق الإخراج القياسي أم لا. |
| virtual [Exceptions](../../aspose.page/saveoptions/exceptions) { get; } | إرجاع قائمة بأخطاء التحويل الملغاة!:SuppressErrors هذا صحيح . |
| [JpegQualityLevel](../../aspose.page/saveoptions/jpegqualitylevel) { get; set; } | تحدد فئة الجودة مستوى الضغط للصورة. تتراوح القيم المتاحة من 0 إلى 100. كلما انخفض الرقم المحدد ، زاد الضغط وبالتالي انخفضت جودة الصورة. ينتج عن قيمة 0 صورة أقل جودة ، بينما ينتج 100 أعلى جودة. |
| virtual [SupressErrors](../../aspose.page/saveoptions/supresserrors) { get; set; } | يحدد ما إذا كان يجب منع الأخطاء أم لا. إذا تمت إضافة الأخطاء الملغاة "true" إلى[`Exceptions`](../../aspose.page/saveoptions/exceptions) list. إذا كان خطأ سينهي الخطأ الأول البرنامج. |

### أنظر أيضا

* class [SaveOptions](../../aspose.page/saveoptions)
* مساحة الاسم [Aspose.Page.EPS.Device](../../aspose.page.eps.device)
* المجسم [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
