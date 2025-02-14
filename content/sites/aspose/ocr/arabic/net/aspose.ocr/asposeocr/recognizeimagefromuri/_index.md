---
title: RecognizeImageFromUri
second_title: Aspose.OCR لمرجع .NET API
description: يتعرف على النص الموجود في الصورة المقدم بواسطة رابط URI .
type: docs
weight: 100
url: /ar/net/aspose.ocr/asposeocr/recognizeimagefromuri/
---
## RecognizeImageFromUri(string) {#recognizeimagefromuri_1}

يتعرف على النص الموجود في الصورة المقدم بواسطة رابط URI .

```csharp
public string RecognizeImageFromUri(string uri)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uri | String | رابط URI للصورة. |

### قيمة الإرجاع

نص تم التعرف عليه.

### ملاحظات

يستخدم التصحيح التلقائي لانحراف الصورة واكتشاف مناطق النص. يدعم GIF و PNG و JPEG و BMP و TIFF .

### أنظر أيضا

* class [AsposeOcr](../../asposeocr)
* مساحة الاسم [Aspose.OCR](../../asposeocr)
* المجسم [Aspose.OCR](../../../)

---

## RecognizeImageFromUri(string, RecognitionSettings) {#recognizeimagefromuri}

يتعرف على النص الموجود على الصورة المقدم من رابط URI.

```csharp
public RecognitionResult RecognizeImageFromUri(string uri, RecognitionSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| uri | String | رابط URI للصورة. |
| settings | RecognitionSettings | إعدادات التعرف. |

### قيمة الإرجاع

ال[`RecognitionResult`](../../recognitionresult) مع نتائج التعرف على الصور.

### ملاحظات

يتعرف على الصورة مع إمكانية التحديد[`RecognitionSettings`](../../recognitionsettings) . يدعم GIF و PNG و JPEG و BMP و TIFF.

### أنظر أيضا

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* مساحة الاسم [Aspose.OCR](../../asposeocr)
* المجسم [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
