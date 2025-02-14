---
title: RemoveChild
second_title: Aspose.Note para la referencia de la API de .NET
description: Elimina el nodo secundario.
type: docs
weight: 140
url: /es/net/aspose.note/notebook/removechild/
---
## Notebook.RemoveChild method

Elimina el nodo secundario.

```csharp
public INotebookChildNode RemoveChild(INotebookChildNode oldChild)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| oldChild | INotebookChildNode | El nodo a eliminar. |

### Valor_devuelto

El nodo eliminado.

### Ejemplos

Muestra cómo acceder a todas las secciones desde un cuaderno.

```csharp
string inputFile = "notebook.onetoc2";
string dataDir = RunExamples.GetDataDir_NoteBook();

Notebook rootNotebook = new Notebook(dataDir + inputFile);

IList<Document> allDocuments = rootNotebook.GetChildNodes<Document>();
foreach (Document document in allDocuments) 
{
    Console.WriteLine(document.DisplayName);
}
```

Muestra cómo eliminar una sección de un bloc de notas.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Cargar un cuaderno de OneNote
var notebook = new Notebook(dataDir + "test.onetoc2");

// Atraviesa sus nodos secundarios para buscar el elemento secundario deseado
foreach (var child in new List<INotebookChildNode>(notebook))
{
    if (child.DisplayName == "Remove Me")
    {
        // Eliminar el elemento secundario del cuaderno
        notebook.RemoveChild(child);
    }
}

dataDir = dataDir + "RemoveChildNode_out.onetoc2";

// Guardar el cuaderno
notebook.Save(dataDir);
```

Muestra cómo guardar un cuaderno.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_NoteBook();

var notebook = new Notebook(dataDir + "test.onetoc2", new NotebookLoadOptions() { DeferredLoading = false });

notebook.Save(dataDir + "notebook_out.onetoc2", new NotebookOneSaveOptions() { DeferredSaving = true});

if (notebook.Any())
{
    var childDocument0 = notebook[0] as Document;

    childDocument0.Save(dataDir + "Not Locked_out.one");

    var childDocument1 = notebook[1] as Document;

    childDocument1.Save(dataDir + "Locked Pass1_out.one", new OneSaveOptions() { DocumentPassword = "pass" });

    var childDocument2 = notebook[2] as Document;

    childDocument2.Save(dataDir + "Locked Pass2_out.one", new OneSaveOptions() { DocumentPassword = "pass2" });
}
```

### Ver también

* interface [INotebookChildNode](../../inotebookchildnode)
* class [Notebook](../../notebook)
* espacio de nombres [Aspose.Note](../../notebook)
* asamblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
