---
title: DetectLayoutChanges
second_title: Aspose.Note لمرجع NET API
description: يكتشف جميع التغييرات التي تم إجراؤها على تخطيط المستند منذ السابقDetectLayoutChangesaspose.note/document/detectlayoutchanges call. في حالةAutomaticLayoutChangesDetectionEnabledaspose.note/document/automaticlayoutchangesdetectionenabled اضبط على صحيح  ويستخدم تلقائيًا في بداية تصدير المستند.
type: docs
weight: 90
url: /ar/net/aspose.note/document/detectlayoutchanges/
---
## Document.DetectLayoutChanges method

يكتشف جميع التغييرات التي تم إجراؤها على تخطيط المستند منذ السابق`DetectLayoutChanges` call. في حالة[`AutomaticLayoutChangesDetectionEnabled`](../automaticlayoutchangesdetectionenabled) اضبط على "صحيح" ، ويستخدم تلقائيًا في بداية تصدير المستند.

```csharp
public void DetectLayoutChanges()
```

### أمثلة

يوضح كيفية حفظ مستند بتنسيقات مختلفة.

```csharp
// المسار إلى دليل المستندات.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// تهيئة المستند الجديد
Document doc = new Document() { AutomaticLayoutChangesDetectionEnabled = false };

// تهيئة الصفحة الجديدة
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// النمط الافتراضي لكل النص في المستند.
ParagraphStyle textStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };
page.Title = new Title(doc)
             {
                 TitleText = new RichText(doc) { Text = "Title text.", ParagraphStyle = textStyle },
                 TitleDate = new RichText(doc) { Text = new DateTime(2011, 11, 11).ToString("D", CultureInfo.InvariantCulture), ParagraphStyle = textStyle },
                 TitleTime = new RichText(doc) { Text = "12:34", ParagraphStyle = textStyle }
             };

// إلحاق عقدة الصفحة
doc.AppendChildLast(page);

// حفظ مستند OneNote بتنسيقات مختلفة وتعيين حجم خط النص واكتشاف تغييرات التخطيط يدويًا.
doc.Save(dataDir + "ConsequentExportOperations_out.html");            
doc.Save(dataDir + "ConsequentExportOperations_out.pdf");            
doc.Save(dataDir + "ConsequentExportOperations_out.jpg");            
textStyle.FontSize = 11;           
doc.DetectLayoutChanges();            
doc.Save(dataDir + "ConsequentExportOperations_out.bmp");
```

### أنظر أيضا

* class [Document](../../document)
* مساحة الاسم [Aspose.Note](../../document)
* المجسم [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
