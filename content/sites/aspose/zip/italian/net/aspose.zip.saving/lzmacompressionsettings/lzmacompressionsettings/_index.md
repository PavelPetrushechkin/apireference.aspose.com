---
title: LzmaCompressionSettings
second_title: Riferimento API Aspose.ZIP per .NET
description: Inizializza una nuova istanza diLzmaCompressionSettingsaspose.zip.saving/lzmacompressionsettings classe con dimensione del dizionario predefinita pari a 16 megabyte.
type: docs
weight: 10
url: /it/net/aspose.zip.saving/lzmacompressionsettings/lzmacompressionsettings/
---
## LzmaCompressionSettings constructor

Inizializza una nuova istanza di[`LzmaCompressionSettings`](../../lzmacompressionsettings) classe con dimensione del dizionario predefinita, pari a 16 megabyte.

```csharp
public LzmaCompressionSettings()
```

### Esempi

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new LzmaCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Guarda anche

* class [LzmaCompressionSettings](../../lzmacompressionsettings)
* spazio dei nomi [Aspose.Zip.Saving](../../lzmacompressionsettings)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
