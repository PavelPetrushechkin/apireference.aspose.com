---
title: CompressionProgressed
second_title: Riferimento API Aspose.ZIP per .NET
description: Aumenta quando una parte del flusso non elaborato viene compressa.
type: docs
weight: 70
url: /it/net/aspose.zip/archiveentry/compressionprogressed/
---
## ArchiveEntry.CompressionProgressed event

Aumenta quando una parte del flusso non elaborato viene compressa.

```csharp
public event EventHandler<ProgressEventArgs> CompressionProgressed;
```

### Osservazioni

Il mittente dell'evento è un[`ArchiveEntry`](../../archiveentry) esempio.

### Esempi

```csharp
archive.Entries[0].CompressionProgressed += (s, e) => { int percent = (int)((100 * (long)e.ProceededBytes) / entrySourceStream.Length); };
```

### Guarda anche

* class [ProgressEventArgs](../../progresseventargs)
* class [ArchiveEntry](../../archiveentry)
* spazio dei nomi [Aspose.Zip](../../archiveentry)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
