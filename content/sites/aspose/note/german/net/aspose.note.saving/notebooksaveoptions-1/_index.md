---
title: NotebookSaveOptionsTDocumentSaveOptions
second_title: Aspose.Note für .NET-API-Referenz
description: Eine abstrakte Basisklasse die Notebook-Speicheroptionen für ein bestimmtes Format darstellt und gemeinsame Speicheroptionen für alle untergeordneten Dokumentknoten bereitstellt.
type: docs
weight: 780
url: /de/net/aspose.note.saving/notebooksaveoptions-1/
---
## NotebookSaveOptions&lt;TDocumentSaveOptions&gt; class

Eine abstrakte Basisklasse, die Notebook-Speicheroptionen für ein bestimmtes Format darstellt und gemeinsame Speicheroptionen für alle untergeordneten Dokumentknoten bereitstellt.

```csharp
public abstract class NotebookSaveOptions<TDocumentSaveOptions> : NotebookSaveOptions
    where TDocumentSaveOptions : SaveOptions
```

| Parameter | Beschreibung |
| --- | --- |
| TDocumentSaveOptions | Die Speicheroptionen für alle untergeordneten Dokumente aller Notizbücher. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DeferredSaving](../../aspose.note.saving/notebooksaveoptions/deferredsaving) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob untergeordnete Dokumente explizit gespeichert werden sollen. |
| [DocumentSaveOptions](../../aspose.note.saving/notebooksaveoptions`1/documentsaveoptions) { get; } | Ruft die Speicheroptionen für alle untergeordneten Dokumente des Notizbuchs ab oder legt sie fest. |
| [Flatten](../../aspose.note.saving/notebooksaveoptions/flatten) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Hierarchie der untergeordneten Notizbücher abgeflacht gespeichert wird. |
| override [SaveFormat](../../aspose.note.saving/notebooksaveoptions`1/saveformat) { get; } | Ruft das Format ab, in dem das Notizbuch gespeichert ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetDocumentSaveOptions](../../aspose.note.saving/notebooksaveoptions`1/getdocumentsaveoptions)() | Ruft die Speicheroptionen für alle untergeordneten Dokumente des Notizbuchs ab. |

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

* class [NotebookSaveOptions](../notebooksaveoptions)
* class [SaveOptions](../saveoptions)
* namensraum [Aspose.Note.Saving](../../aspose.note.saving)
* Montage [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
