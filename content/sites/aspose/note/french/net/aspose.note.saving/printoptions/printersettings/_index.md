---
title: PrinterSettings
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient ou définit les paramètres de limprimante.
type: docs
weight: 40
url: /fr/net/aspose.note.saving/printoptions/printersettings/
---
## PrintOptions.PrinterSettings property

Obtient ou définit les paramètres de l'imprimante.

```csharp
public PrinterSettings PrinterSettings { get; set; }
```

### Exemples

Montre comment envoyer un document à une imprimante à l'aide de la boîte de dialogue Windows standard avec les options spécifiées.

```csharp
// Le chemin d'accès au répertoire des documents.
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

### Voir également

* class [PrintOptions](../../printoptions)
* espace de noms [Aspose.Note.Saving](../../printoptions)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
