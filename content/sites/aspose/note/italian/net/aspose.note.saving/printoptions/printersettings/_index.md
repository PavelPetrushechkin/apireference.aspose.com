---
title: PrinterSettings
second_title: Aspose.Note per .NET API Reference
description: Ottiene o imposta le impostazioni della stampante.
type: docs
weight: 40
url: /it/net/aspose.note.saving/printoptions/printersettings/
---
## PrintOptions.PrinterSettings property

Ottiene o imposta le impostazioni della stampante.

```csharp
public PrinterSettings PrinterSettings { get; set; }
```

### Esempi

Mostra come inviare un documento a una stampante utilizzando la finestra di dialogo standard di Windows con le opzioni specificate.

```csharp
// Il percorso della directory dei documenti.
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

### Guarda anche

* class [PrintOptions](../../printoptions)
* spazio dei nomi [Aspose.Note.Saving](../../printoptions)
* assemblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
