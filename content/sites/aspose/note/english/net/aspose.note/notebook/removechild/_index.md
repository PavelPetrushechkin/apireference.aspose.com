---
title: RemoveChild
second_title: Aspose.Note for .NET API Reference
description: Removes the child node.
type: docs
weight: 140
url: /net/aspose.note/notebook/removechild/
---
## Notebook.RemoveChild method

Removes the child node.

```csharp
public INotebookChildNode RemoveChild(INotebookChildNode oldChild)
```

| Parameter | Type | Description |
| --- | --- | --- |
| oldChild | INotebookChildNode | The node to remove. |

### Return Value

The removed node.

### Examples

Shows how to access all sections from a notebook.

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

Shows how to remove a section from a notebook.

```csharp
// The path to the documents directory.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Load a OneNote Notebook
var notebook = new Notebook(dataDir + "test.onetoc2");

// Traverse through its child nodes for searching the desired child item
foreach (var child in new List<INotebookChildNode>(notebook))
{
    if (child.DisplayName == "Remove Me")
    {
        // Remove the Child Item from the Notebook
        notebook.RemoveChild(child);
    }
}

dataDir = dataDir + "RemoveChildNode_out.onetoc2";

// Save the Notebook
notebook.Save(dataDir);
```

Shows how to save a notebook.

```csharp
// The path to the documents directory.
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

### See Also

* interface [INotebookChildNode](../../inotebookchildnode)
* class [Notebook](../../notebook)
* namespace [Aspose.Note](../../notebook)
* assembly [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
