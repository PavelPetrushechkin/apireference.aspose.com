---
title: Save
second_title: Aspose.ZIP لمرجع .NET API
description: يحفظ أرشيف lzma إلى الدفق المقدم.
type: docs
weight: 40
url: /ar/net/aspose.zip.lzma/lzmaarchive/save/
---
## Save(Stream) {#save_1}

يحفظ أرشيف lzma إلى الدفق المقدم.

```csharp
public void Save(Stream output)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| output | Stream | تيار الوجهة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | *output* لا يدعم السعي. |
| ArgumentNullException | *output* باطل. |

### ملاحظات

*output* يجب أن يكون قابلاً للبحث.

### أمثلة

```csharp
using (FileStream lzmaFile = File.Open("archive.lzma", FileMode.Create))
{
    using (var archive = new LzmaArchive())
    {
        archive.SetSource("data.bin");
        archive.Save(lzmaFile);
     }
}
```

### أنظر أيضا

* class [LzmaArchive](../../lzmaarchive)
* مساحة الاسم [Aspose.Zip.LZMA](../../lzmaarchive)
* المجسم [Aspose.Zip](../../../)

---

## Save(FileInfo) {#save}

يحفظ أرشيف lzma إلى ملف الوجهة المقدم.

```csharp
public void Save(FileInfo destination)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destination | FileInfo | FileInfo الذي سيتم فتحه كتدفق الوجهة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| SecurityException | المتصل ليس لديه الإذن المطلوب لفتح*destination*. |
| ArgumentException | مسار الملف فارغ أو يحتوي على مسافات بيضاء فقط. |
| FileNotFoundException | لم يتم العثور على الملف. |
| UnauthorizedAccessException | مسار الملف للقراءة فقط أو هو دليل. |
| ArgumentNullException | *destination* باطل. |
| DirectoryNotFoundException | المسار المحدد غير صالح ، مثل وجوده على محرك أقراص غير معين. |
| IOException | الملف مفتوح بالفعل. |

### أمثلة

```csharp
using (var archive = new LzmaArchive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save(new FileInfo("archive.lzma"));
}
```

### أنظر أيضا

* class [LzmaArchive](../../lzmaarchive)
* مساحة الاسم [Aspose.Zip.LZMA](../../lzmaarchive)
* المجسم [Aspose.Zip](../../../)

---

## Save(string) {#save_2}

يحفظ أرشيف lzma إلى ملف الوجهة المقدم.

```csharp
public void Save(string destinationFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destinationFileName | String | مسار الأرشيف المراد إنشاؤه. إذا كان اسم الملف المحدد يشير إلى ملف موجود ، فسيتم استبداله. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *destinationFileName* باطل. |
| SecurityException | المتصل ليس لديه الإذن المطلوب للوصول |
| ArgumentException | ال*destinationFileName* فارغ أو يحتوي على مسافات بيضاء فقط أو يحتوي على أحرف غير صالحة. |
| UnauthorizedAccessException | الوصول إلى الملف*destinationFileName* مرفوض. |
| PathTooLongException | المحدد*destinationFileName*أو اسم الملف أو كلاهما يتجاوز الحد الأقصى للطول المحدد من قبل النظام. على سبيل المثال ، في الأنظمة الأساسية المستندة إلى Windows ، يجب أن تكون المسارات أقل من 248 حرفًا ، ويجب أن تكون أسماء الملفات أقل من 260 حرفًا. |
| NotSupportedException | ملف في*destinationFileName* يحتوي على نقطتين (:) في منتصف السلسلة. |

### أمثلة

```csharp
using (var archive = new LzmaArchive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save("result.lzma");
}
```

### أنظر أيضا

* class [LzmaArchive](../../lzmaarchive)
* مساحة الاسم [Aspose.Zip.LZMA](../../lzmaarchive)
* المجسم [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
