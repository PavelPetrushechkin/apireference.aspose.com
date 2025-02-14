---
title: SetOpen
second_title: Aspose.Note per .NET API Reference
description: Imposta il tag per aprire lo stato.
type: docs
weight: 80
url: /it/net/aspose.note/checkbox/setopen/
---
## CheckBox.SetOpen method

Imposta il tag per aprire lo stato.

```csharp
public virtual void SetOpen()
```

### Esempi

Mostra come aprire tutte le caselle di controllo relative al "Progetto C".

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_Tags();

// Carica il documento in Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, ClosedProjectCNotesFileName));

foreach (var node in oneFile.GetChildNodes<ITaggable>())
{
    foreach (var checkBox in node.Tags.OfType<CheckBox>())
    {
        if (checkBox.Label.Contains("Project C") && checkBox.Checked)
        {
            checkBox.SetOpen();
        }
    }
}

oneFile.Save(Path.Combine(dataDir, "ProjectNoteWithOpenProjectC.one"));
```

### Guarda anche

* class [CheckBox](../../checkbox)
* spazio dei nomi [Aspose.Note](../../checkbox)
* assemblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
