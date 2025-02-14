---
title: LoadChildDocument
second_title: Référence de l'API Aspose.Note pour .NET
description: Ajoute un nœud de document enfant. Ouvre un document OneNote existant à partir dun fichier.
type: docs
weight: 120
url: /fr/net/aspose.note/notebook/loadchilddocument/
---
## LoadChildDocument(string) {#loadchilddocument_2}

Ajoute un nœud de document enfant. Ouvre un document OneNote existant à partir d'un fichier.

```csharp
public void LoadChildDocument(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |

### Exemples

Montre comment charger un bloc-notes à partir d'un flux.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_NoteBook();

FileStream stream = new FileStream(dataDir + "Notizbuch öffnen.onetoc2", FileMode.Open);

var notebook = new Notebook(stream);

using (FileStream childStream = new FileStream(dataDir + "Aspose.one", FileMode.Open))
{
    notebook.LoadChildDocument(childStream);
}

notebook.LoadChildDocument(dataDir + "Sample1.one");
```

### Voir également

* class [Notebook](../../notebook)
* espace de noms [Aspose.Note](../../notebook)
* Assemblée [Aspose.Note](../../../)

---

## LoadChildDocument(string, LoadOptions) {#loadchilddocument_3}

Ajoute un nœud de document enfant. Ouvre un document OneNote existant à partir d'un fichier. Permet de spécifier des options de chargement supplémentaires.

```csharp
public void LoadChildDocument(string filePath, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [Notebook](../../notebook)
* espace de noms [Aspose.Note](../../notebook)
* Assemblée [Aspose.Note](../../../)

---

## LoadChildDocument(Stream) {#loadchilddocument}

Ajoute un nœud de document enfant. Ouvre un document OneNote existant à partir d'un flux.

```csharp
public void LoadChildDocument(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |

### Exemples

Montre comment charger un bloc-notes à partir d'un flux.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_NoteBook();

FileStream stream = new FileStream(dataDir + "Notizbuch öffnen.onetoc2", FileMode.Open);

var notebook = new Notebook(stream);

using (FileStream childStream = new FileStream(dataDir + "Aspose.one", FileMode.Open))
{
    notebook.LoadChildDocument(childStream);
}

notebook.LoadChildDocument(dataDir + "Sample1.one");
```

### Voir également

* class [Notebook](../../notebook)
* espace de noms [Aspose.Note](../../notebook)
* Assemblée [Aspose.Note](../../../)

---

## LoadChildDocument(Stream, LoadOptions) {#loadchilddocument_1}

Ajoute un nœud de document enfant. Ouvre un document OneNote existant à partir d'un flux. Permet de spécifier des options de chargement supplémentaires.

```csharp
public void LoadChildDocument(Stream stream, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [LoadOptions](../../loadoptions)
* class [Notebook](../../notebook)
* espace de noms [Aspose.Note](../../notebook)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
