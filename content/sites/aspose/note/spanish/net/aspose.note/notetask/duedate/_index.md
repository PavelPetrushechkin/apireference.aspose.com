---
title: DueDate
second_title: Aspose.Note para la referencia de la API de .NET
description: Obtiene o establece la fecha de vencimiento.
type: docs
weight: 70
url: /es/net/aspose.note/notetask/duedate/
---
## NoteTask.DueDate property

Obtiene o establece la fecha de vencimiento.

```csharp
public DateTime DueDate { get; set; }
```

### El valor de la propiedad

ElDateTime .

### Ejemplos

Muestra cómo generar un pdf que contenga todas las páginas relacionadas con el 'Proyecto A'.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tags();

// Cargue el documento en Aspose.Note.
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

Muestra cómo acceder a los detalles de las tareas de Outlook.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tasks();

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Obtener todos los nodos RichText
IList<RichText> nodes = oneFile.GetChildNodes<RichText>();

// Iterar a través de cada nodo
foreach (RichText richText in nodes)
{
    var tasks = richText.Tags.OfType<NoteTask>();
    if (tasks.Any())
    {
        Console.WriteLine($"Task: {richText.Text}");
        foreach (var noteTask in tasks)
        {
            // Recuperar propiedades
            Console.WriteLine($"    Completed Time: {noteTask.CompletedTime}");
            Console.WriteLine($"    Create Time: {noteTask.CreationTime}");
            Console.WriteLine($"    Due Date: {noteTask.DueDate}");
            Console.WriteLine($"    Status: {noteTask.Status}");
            Console.WriteLine($"    Icon: {noteTask.Icon}");
        }
    }
}
```

### Ver también

* class [NoteTask](../../notetask)
* espacio de nombres [Aspose.Note](../../notetask)
* asamblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
