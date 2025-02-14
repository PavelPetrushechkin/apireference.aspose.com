---
title: SevenZipArchive
second_title: Riferimento API Aspose.ZIP per .NET
description: Inizializza una nuova istanza diSevenZipArchiveaspose.zip.sevenzip/sevenziparchiveclasse con impostazioni opzionali per le sue voci.
type: docs
weight: 10
url: /it/net/aspose.zip.sevenzip/sevenziparchive/sevenziparchive/
---
## SevenZipArchive(SevenZipEntrySettings) {#constructor}

Inizializza una nuova istanza di[`SevenZipArchive`](../../sevenziparchive)classe con impostazioni opzionali per le sue voci.

```csharp
public SevenZipArchive(SevenZipEntrySettings newEntrySettings = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newEntrySettings | SevenZipEntrySettings | Impostazioni di compressione e crittografia utilizzate per le nuove aggiunte[`SevenZipArchiveEntry`](../../sevenziparchiveentry) items. Se non specificato, verrebbe utilizzata la compressione LZMA senza crittografia. |

### Esempi

L'esempio seguente mostra come comprimere un singolo file con le impostazioni predefinite: Compressione LZMA senza crittografia.

```csharp
using (FileStream sevenZipFile = File.Open("archive.7z", FileMode.Create))
{
    using (var archive = new SevenZipArchive())
    {
        archive.CreateEntry("data.bin", "file.dat");
        archive.Save(sevenZipFile);
    }
}
```

### Guarda anche

* class [SevenZipEntrySettings](../../../aspose.zip.saving/sevenzipentrysettings)
* class [SevenZipArchive](../../sevenziparchive)
* spazio dei nomi [Aspose.Zip.SevenZip](../../sevenziparchive)
* assemblea [Aspose.Zip](../../../)

---

## SevenZipArchive(Stream) {#constructor_1}

Inizializza una nuova istanza di[`SevenZipArchive`](../../sevenziparchive) classe e compone l'elenco delle voci può essere estratto dall'archivio.

```csharp
public SevenZipArchive(Stream sourceStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStream | Stream | La fonte dell'archivio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *sourceStream* non è ricercabile. |
| ArgumentNullException | *sourceStream* è zero. |
| NotImplementedException | L'archivio contiene più di un codificatore. Ora è supportata solo la compressione LZMA. |

### Osservazioni

Questo costruttore non decomprime alcuna voce. Vedere[`ExtractToDirectory`](../extracttodirectory) metodo per la decompressione.

### Esempi

```csharp
using (SevenZipArchive archive = new SevenZipArchive(File.OpenRead("archive.7z")))
{
    archive.ExtractToDirectory("C:\\extracted");
}
```

### Guarda anche

* class [SevenZipArchive](../../sevenziparchive)
* spazio dei nomi [Aspose.Zip.SevenZip](../../sevenziparchive)
* assemblea [Aspose.Zip](../../../)

---

## SevenZipArchive(string) {#constructor_2}

Inizializza una nuova istanza di[`SevenZipArchive`](../../sevenziparchive) classe e compone l'elenco delle voci può essere estratto dall'archivio.

```csharp
public SevenZipArchive(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Il percorso completo o relativo al file di archivio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *path* è zero. |
| SecurityException | Il chiamante non dispone dell'autorizzazione richiesta per accedere |
| ArgumentException | Il*path* è vuoto, contiene solo spazi bianchi o contiene caratteri non validi. |
| UnauthorizedAccessException | Accesso al file*path* è negato. |
| PathTooLongException | Il specificato*path*, il nome del file o entrambi superano la lunghezza massima definita dal sistema. Ad esempio, sulle piattaforme basate su Windows, i percorsi devono essere inferiori a 248 caratteri e i nomi dei file devono essere inferiori a 260 caratteri. |
| NotSupportedException | Archivia a*path* contiene due punti (:) al centro della stringa. |

### Osservazioni

Questo costruttore non decomprime alcuna voce. Vedere[`ExtractToDirectory`](../extracttodirectory) metodo per la decompressione.

### Esempi

```csharp
using (SevenZipArchive archive = new SevenZipArchive("archive.7z"))
{
    archive.ExtractToDirectory("C:\\extracted");
}
```

### Guarda anche

* class [SevenZipArchive](../../sevenziparchive)
* spazio dei nomi [Aspose.Zip.SevenZip](../../sevenziparchive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
