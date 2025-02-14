---
title: DueDate
second_title: Aspose.Note per .NET API Reference
description: Ottiene o imposta la data di scadenza.
type: docs
weight: 70
url: /it/net/aspose.note/notetask/duedate/
---
## NoteTask.DueDate property

Ottiene o imposta la data di scadenza.

```csharp
public DateTime DueDate { get; set; }
```

### Valore della proprietà

IlDateTime .

### Esempi

Mostra come generare un pdf contenente tutte le pagine relative al 'Progetto A'.

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_Tags();

// Carica il documento in Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, "ProjectNotes.one"));

var report = new Document();
foreach (var page in oneFile)
{
    if (page.GetChildNodes<ITaggable>().Any(e => e.Tags.Any(x => x.Label.Contains("Project A"))))
    {
        report.AppendChildLast(page.Clone());
    }
}

report.Save(Path.Combine(dataDir, "ProjectA_Report.pdf"));
```

Mostra come accedere ai dettagli delle attività di Outlook.

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_Tasks();

// Carica il documento in Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Ottieni tutti i nodi RichText
IList<RichText> nodes = oneFile.GetChildNodes<RichText>();

// Scorri ogni nodo
foreach (RichText richText in nodes)
{
    var tasks = richText.Tags.OfType<NoteTask>();
    if (tasks.Any())
    {
        Console.WriteLine($"Task: {richText.Text}");
        foreach (var noteTask in tasks)
        {
            // Recupera le proprietà
            Console.WriteLine($"    Completed Time: {noteTask.CompletedTime}");
            Console.WriteLine($"    Create Time: {noteTask.CreationTime}");
            Console.WriteLine($"    Due Date: {noteTask.DueDate}");
            Console.WriteLine($"    Status: {noteTask.Status}");
            Console.WriteLine($"    Icon: {noteTask.Icon}");
        }
    }
}
```

### Guarda anche

* class [NoteTask](../../notetask)
* spazio dei nomi [Aspose.Note](../../notetask)
* assemblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
