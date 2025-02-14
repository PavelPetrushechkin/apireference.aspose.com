---
title: DisplayName
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient ou définit le nom daffichage.
type: docs
weight: 40
url: /fr/net/aspose.note/notebook/displayname/
---
## Notebook.DisplayName property

Obtient ou définit le nom d'affichage.

```csharp
public string DisplayName { get; set; }
```

### Exemples

Montre comment supprimer une section d'un bloc-notes.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_NoteBook();

// Charger un bloc-notes OneNote
var notebook = new Notebook(dataDir + "test.onetoc2");

// Parcourt ses nœuds enfants pour rechercher l'élément enfant souhaité
foreach (var child in new List<INotebookChildNode>(notebook))
{
    if (child.DisplayName == "Remove Me")
    {
        // Supprimer l'élément enfant du bloc-notes
        notebook.RemoveChild(child);
    }
}

dataDir = dataDir + "RemoveChildNode_out.onetoc2";

// Enregistrer le bloc-notes
notebook.Save(dataDir);
```

### Voir également

* class [Notebook](../../notebook)
* espace de noms [Aspose.Note](../../notebook)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
