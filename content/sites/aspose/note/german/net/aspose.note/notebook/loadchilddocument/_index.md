---
title: LoadChildDocument
second_title: Aspose.Note für .NET-API-Referenz
description: Fügt einen untergeordneten Dokumentknoten hinzu. Öffnet ein vorhandenes OneNote-Dokument aus einer Datei.
type: docs
weight: 120
url: /de/net/aspose.note/notebook/loadchilddocument/
---
## LoadChildDocument(string) {#loadchilddocument_2}

Fügt einen untergeordneten Dokumentknoten hinzu. Öffnet ein vorhandenes OneNote-Dokument aus einer Datei.

```csharp
public void LoadChildDocument(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |

### Beispiele

Zeigt, wie ein Notebook aus einem Stream geladen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_NoteBook();

FileStream stream = new FileStream(dataDir + "Notizbuch öffnen.onetoc2", FileMode.Open);

var notebook = new Notebook(stream);

using (FileStream childStream = new FileStream(dataDir + "Aspose.one", FileMode.Open))
{
    notebook.LoadChildDocument(childStream);
}

notebook.LoadChildDocument(dataDir + "Sample1.one");
```

### Siehe auch

* class [Notebook](../../notebook)
* namensraum [Aspose.Note](../../notebook)
* Montage [Aspose.Note](../../../)

---

## LoadChildDocument(string, LoadOptions) {#loadchilddocument_3}

Fügt einen untergeordneten Dokumentknoten hinzu. Öffnet ein vorhandenes OneNote-Dokument aus einer Datei. Ermöglicht die Angabe zusätzlicher Ladeoptionen.

```csharp
public void LoadChildDocument(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [Notebook](../../notebook)
* namensraum [Aspose.Note](../../notebook)
* Montage [Aspose.Note](../../../)

---

## LoadChildDocument(Stream) {#loadchilddocument}

Fügt einen untergeordneten Dokumentknoten hinzu. Öffnet ein vorhandenes OneNote-Dokument aus einem Stream.

```csharp
public void LoadChildDocument(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |

### Beispiele

Zeigt, wie ein Notebook aus einem Stream geladen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_NoteBook();

FileStream stream = new FileStream(dataDir + "Notizbuch öffnen.onetoc2", FileMode.Open);

var notebook = new Notebook(stream);

using (FileStream childStream = new FileStream(dataDir + "Aspose.one", FileMode.Open))
{
    notebook.LoadChildDocument(childStream);
}

notebook.LoadChildDocument(dataDir + "Sample1.one");
```

### Siehe auch

* class [Notebook](../../notebook)
* namensraum [Aspose.Note](../../notebook)
* Montage [Aspose.Note](../../../)

---

## LoadChildDocument(Stream, LoadOptions) {#loadchilddocument_1}

Fügt einen untergeordneten Dokumentknoten hinzu. Öffnet ein vorhandenes OneNote-Dokument aus einem Stream. Ermöglicht die Angabe zusätzlicher Ladeoptionen.

```csharp
public void LoadChildDocument(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [Notebook](../../notebook)
* namensraum [Aspose.Note](../../notebook)
* Montage [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
