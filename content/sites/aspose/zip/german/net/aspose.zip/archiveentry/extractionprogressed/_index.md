---
title: ExtractionProgressed
second_title: Aspose.ZIP für .NET-API-Referenz
description: Wird ausgelöst wenn ein Teil des Rohdatenstroms extrahiert wird.
type: docs
weight: 80
url: /de/net/aspose.zip/archiveentry/extractionprogressed/
---
## ArchiveEntry.ExtractionProgressed event

Wird ausgelöst, wenn ein Teil des Rohdatenstroms extrahiert wird.

```csharp
public event EventHandler<ProgressEventArgs> ExtractionProgressed;
```

### Bemerkungen

Ereignissender ist ein[`ArchiveEntry`](../../archiveentry) Beispiel.

### Beispiele

```csharp
archive.Entries[0].ExtractionProgressed += (s, e) => {  int percent = (int)((100 * e.ProceededBytes) / ((ArchiveEntry)s).UncompressedSize); };
```

### Siehe auch

* class [ProgressEventArgs](../../progresseventargs)
* class [ArchiveEntry](../../archiveentry)
* namensraum [Aspose.Zip](../../archiveentry)
* Montage [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
