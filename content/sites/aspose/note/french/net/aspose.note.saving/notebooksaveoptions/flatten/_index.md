---
title: Flatten
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient ou définit une valeur indiquant si la hiérarchie des enfants du bloc-notes est enregistrée à plat.
type: docs
weight: 20
url: /fr/net/aspose.note.saving/notebooksaveoptions/flatten/
---
## NotebookSaveOptions.Flatten property

Obtient ou définit une valeur indiquant si la hiérarchie des enfants du bloc-notes est enregistrée à plat.

```csharp
public bool Flatten { get; set; }
```

### Exemples

Montre comment enregistrer un cahier aplati au format pdf.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Charger un bloc-notes OneNote
var notebook = new Notebook(dataDir + "Notizbuch �ffnen.onetoc2");

// Enregistrer le bloc-notes
dataDir = dataDir + "ConvertToPDFAsFlattened_out.pdf";
notebook.Save(
    dataDir,
    new NotebookPdfSaveOptions
    {
        Flatten = true
    });
```

Montre comment enregistrer un cahier aplati en tant qu'image.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Charger un bloc-notes OneNote
var notebook = new Notebook(dataDir + "Notizbuch öffnen.onetoc2");

var notebookSaveOptions = new NotebookImageSaveOptions(SaveFormat.Png);

var documentSaveOptions = notebookSaveOptions.DocumentSaveOptions;

documentSaveOptions.Resolution = 400;
notebookSaveOptions.Flatten = true;

dataDir = dataDir + "ConvertToImageAsFlattenedNotebook_out.png";

// Enregistrer le bloc-notes
notebook.Save(dataDir, notebookSaveOptions);
```

### Voir également

* class [NotebookSaveOptions](../../notebooksaveoptions)
* espace de noms [Aspose.Note.Saving](../../notebooksaveoptions)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
