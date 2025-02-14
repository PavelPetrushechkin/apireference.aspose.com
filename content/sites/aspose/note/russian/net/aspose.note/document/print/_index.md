---
title: Print
second_title: Справочник по API Aspose.Note для .NET
description: Печать документа на принтере по умолчанию.
type: docs
weight: 130
url: /ru/net/aspose.note/document/print/
---
## Print() {#print}

Печать документа на принтере по умолчанию.

```csharp
public void Print()
```

### Примеры

Показывает, как отправить документ на принтер с помощью стандартного диалогового окна Windows с параметрами по умолчанию.

```csharp
// Путь к каталогу документов.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

var document = new Aspose.Note.Document(dataDir + "Aspose.one");

document.Print();
```

Показывает, как отправить документ на принтер, используя стандартный диалог Windows с заданными параметрами.

```csharp
// Путь к каталогу документов.
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

### Смотрите также

* class [Document](../../document)
* пространство имен [Aspose.Note](../../document)
* сборка [Aspose.Note](../../../)

---

## Print(PrintOptions) {#print_1}

Печать документа на принтере по умолчанию.

```csharp
public void Print(PrintOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | PrintOptions | Параметры, используемые для печати документа. Может быть нулевым. |

### Смотрите также

* class [PrintOptions](../../../aspose.note.saving/printoptions)
* class [Document](../../document)
* пространство имен [Aspose.Note](../../document)
* сборка [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
