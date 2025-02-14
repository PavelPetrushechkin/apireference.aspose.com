---
title: DisplayName
second_title: Aspose.Note per .NET API Reference
description: Ottiene o imposta il nome visualizzato.
type: docs
weight: 40
url: /it/net/aspose.note/notebook/displayname/
---
## Notebook.DisplayName property

Ottiene o imposta il nome visualizzato.

```csharp
public string DisplayName { get; set; }
```

### Esempi

Mostra come rimuovere una sezione da un blocco appunti.

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Carica un blocco appunti di OneNote
var notebook = new Notebook(dataDir + "test.onetoc2");

// Attraversa i suoi nodi figlio per cercare l'elemento figlio desiderato
foreach (var child in new List<INotebookChildNode>(notebook))
{
    if (child.DisplayName == "Remove Me")
    {
        // Rimuovi l'elemento figlio dal taccuino
        notebook.RemoveChild(child);
    }
}

dataDir = dataDir + "RemoveChildNode_out.onetoc2";

// Salva il taccuino
notebook.Save(dataDir);
```

### Guarda anche

* class [Notebook](../../notebook)
* spazio dei nomi [Aspose.Note](../../notebook)
* assemblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
