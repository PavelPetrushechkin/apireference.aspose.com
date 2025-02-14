---
title: DocumentSaveOptions
second_title: Aspose.Note für .NET-API-Referenz
description: Ruft die Speicheroptionen für alle untergeordneten Dokumente des Notizbuchs ab oder legt sie fest.
type: docs
weight: 10
url: /de/net/aspose.note.saving/notebooksaveoptions-1/documentsaveoptions/
---
## NotebookSaveOptions&lt;TDocumentSaveOptions&gt;.DocumentSaveOptions property

Ruft die Speicheroptionen für alle untergeordneten Dokumente des Notizbuchs ab oder legt sie fest.

```csharp
public TDocumentSaveOptions DocumentSaveOptions { get; }
```

### Beispiele

Zeigt, wie Notizbücher im PDF-Format mit den angegebenen Optionen gespeichert werden.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Ein OneNote-Notizbuch laden
var notebook = new Notebook(dataDir + "Notizbuch �ffnen.onetoc2");

var notebookSaveOptions = new NotebookPdfSaveOptions();

var documentSaveOptions = notebookSaveOptions.DocumentSaveOptions;

documentSaveOptions.PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm();

dataDir = dataDir + "ConvertToPDF_out.pdf";

// Speichern Sie das Notizbuch
notebook.Save(dataDir, notebookSaveOptions);
```

### Siehe auch

* class [NotebookSaveOptions&lt;TDocumentSaveOptions&gt;](../../notebooksaveoptions-1)
* namensraum [Aspose.Note.Saving](../../notebooksaveoptions-1)
* Montage [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
