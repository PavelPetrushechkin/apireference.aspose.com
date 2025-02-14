---
title: PrinterSettings
second_title: Справочник по API Aspose.Note для .NET
description: Получает или устанавливает параметры принтера.
type: docs
weight: 40
url: /ru/net/aspose.note.saving/printoptions/printersettings/
---
## PrintOptions.PrinterSettings property

Получает или устанавливает параметры принтера.

```csharp
public PrinterSettings PrinterSettings { get; set; }
```

### Примеры

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

* class [PrintOptions](../../printoptions)
* пространство имен [Aspose.Note.Saving](../../printoptions)
* сборка [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
