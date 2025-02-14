---
title: Print
second_title: Aspose.Note لمرجع NET API
description: طباعة المستند باستخدام الطابعة الافتراضية.
type: docs
weight: 130
url: /ar/net/aspose.note/document/print/
---
## Print() {#print}

طباعة المستند باستخدام الطابعة الافتراضية.

```csharp
public void Print()
```

### أمثلة

يوضح كيفية إرسال المستند إلى الطابعة باستخدام مربع حوار Windows القياسي مع الخيارات الافتراضية.

```csharp
// المسار إلى دليل المستندات.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

var document = new Aspose.Note.Document(dataDir + "Aspose.one");

document.Print();
```

يوضح كيفية إرسال المستند إلى طابعة باستخدام مربع حوار Windows القياسي مع خيارات محددة.

```csharp
// المسار إلى دليل المستندات.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

var document = new Aspose.Note.Document(dataDir + "Aspose.one");

var printerSettings = new PrinterSettings() { FromPage = 0, ToPage = 10 };
printerSettings.DefaultPageSettings.Landscape = true;
printerSettings.DefaultPageSettings.Margins = new System.Drawing.Printing.Margins(50, 50, 150, 50);

document.Print(new PrintOptions()
               {
                   PrinterSettings = printerSettings,
                   Resolution = 1200,
                   PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm(),
                   DocumentName = "Test.one"
               });
```

### أنظر أيضا

* class [Document](../../document)
* مساحة الاسم [Aspose.Note](../../document)
* المجسم [Aspose.Note](../../../)

---

## Print(PrintOptions) {#print_1}

طباعة المستند باستخدام الطابعة الافتراضية.

```csharp
public void Print(PrintOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | PrintOptions | الخيارات المستخدمة لطباعة مستند. يمكن أن يكون فارغًا. |

### أنظر أيضا

* class [PrintOptions](../../../aspose.note.saving/printoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Note](../../document)
* المجسم [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
