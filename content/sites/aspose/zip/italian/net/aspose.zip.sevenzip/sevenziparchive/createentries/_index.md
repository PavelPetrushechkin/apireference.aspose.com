---
title: CreateEntries
second_title: Riferimento API Aspose.ZIP per .NET
description: Aggiunge allarchivio tutti i file e le directory in modo ricorsivo nella directory data.
type: docs
weight: 40
url: /it/net/aspose.zip.sevenzip/sevenziparchive/createentries/
---
## CreateEntries(DirectoryInfo, bool) {#createentries}

Aggiunge all'archivio tutti i file e le directory in modo ricorsivo nella directory data.

```csharp
public SevenZipArchive CreateEntries(DirectoryInfo directory, bool includeRootDirectory = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| directory | DirectoryInfo | Directory da comprimere. |
| includeRootDirectory | Boolean | Indica se includere o meno la directory radice stessa. |

### Valore di ritorno

L'archivio con le voci composte.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| DirectoryNotFoundException | Il percorso verso*directory* non è valido, ad esempio su un'unità non mappata. |
| SecurityException | Il chiamante non dispone dell'autorizzazione richiesta per accedere*directory*. |

### Esempi

```csharp
using (SevenZipArchive archive = new SevenZipArchive())
{
    DirectoryInfo folder = new DirectoryInfo("C:\folder");
    archive.CreateEntries(folder);
    archive.Save("folder.7z");
}
```

### Guarda anche

* class [SevenZipArchive](../../sevenziparchive)
* spazio dei nomi [Aspose.Zip.SevenZip](../../sevenziparchive)
* assemblea [Aspose.Zip](../../../)

---

## CreateEntries(string, bool) {#createentries_1}

Aggiunge all'archivio tutti i file e le directory in modo ricorsivo nella directory data.

```csharp
public SevenZipArchive CreateEntries(string sourceDirectory, bool includeRootDirectory = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceDirectory | String | Directory da comprimere. |
| includeRootDirectory | Boolean | Indica se includere o meno la directory radice stessa. |

### Valore di ritorno

L'archivio con le voci composte.

### Esempi

Componi l'archivio 7z con la compressione LZMA2.

```csharp
using (SevenZipArchive archive = new SevenZipArchive(new SevenZipEntrySettings(new SevenZipLZMACompressionSettings())))
{
    archive.CreateEntries("C:\folder");
    archive.Save("folder.7z");
}
```

### Guarda anche

* class [SevenZipArchive](../../sevenziparchive)
* spazio dei nomi [Aspose.Zip.SevenZip](../../sevenziparchive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
