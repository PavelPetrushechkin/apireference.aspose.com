---
title: DocumentPassword
second_title: Aspose.Note لمرجع NET API
description: الحصول على أو تعيين كلمة مرور لتشفير محتوى المستند.
type: docs
weight: 20
url: /ar/net/aspose.note.saving/onesaveoptions/documentpassword/
---
## OneSaveOptions.DocumentPassword property

الحصول على أو تعيين كلمة مرور لتشفير محتوى المستند.

```csharp
public string DocumentPassword { get; set; }
```

### أمثلة

يوضح كيفية حفظ المستند مع التشفير.

```csharp
// المسار إلى دليل المستندات.
string dataDir = RunExamples.GetDataDir_NoteBook();

Document document = new Document();
document.Save(dataDir + "CreatingPasswordProtectedDoc_out.one", new OneSaveOptions() { DocumentPassword = "pass" });
```

### أنظر أيضا

* class [OneSaveOptions](../../onesaveoptions)
* مساحة الاسم [Aspose.Note.Saving](../../onesaveoptions)
* المجسم [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
