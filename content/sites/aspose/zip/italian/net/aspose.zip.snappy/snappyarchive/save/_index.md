---
title: Save
second_title: Riferimento API Aspose.ZIP per .NET
description: Salva larchivio scattante nello stream fornito.
type: docs
weight: 40
url: /it/net/aspose.zip.snappy/snappyarchive/save/
---
## Save(Stream) {#save_1}

Salva l'archivio scattante nello stream fornito.

```csharp
public void Save(Stream output)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | Stream | Flusso di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | *output* non supporta la ricerca. |
| ArgumentNullException | *output* è zero. |

### Osservazioni

*output* deve essere ricercabile.

### Esempi

```csharp
using (FileStream snappyFile = File.Open("archive.snappy", FileMode.Create))
{
    using (var archive = new SnappyArchive())
    {
        archive.SetSource("data.bin");
        archive.Save(snappyFile);
     }
}
```

### Guarda anche

* class [SnappyArchive](../../snappyarchive)
* spazio dei nomi [Aspose.Zip.Snappy](../../snappyarchive)
* assemblea [Aspose.Zip](../../../)

---

## Save(FileInfo) {#save}

Salva l'archivio scattante nel file di destinazione fornito.

```csharp
public void Save(FileInfo destination)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destination | FileInfo | FileInfo che verrà aperto come flusso di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| SecurityException | Il chiamante non dispone dell'autorizzazione richiesta per aprire il file*destination*. |
| ArgumentException | Il percorso del file è vuoto o contiene solo spazi bianchi. |
| FileNotFoundException | Il file non è stato trovato. |
| UnauthorizedAccessException | Il percorso del file è di sola lettura o è una directory. |
| ArgumentNullException | *destination* è zero. |
| DirectoryNotFoundException | Il percorso specificato non è valido, ad esempio su un'unità non mappata. |
| IOException | Il file è già aperto. |

### Esempi

```csharp
using (var archive = new SnappyArchive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save(new FileInfo("archive.snappy"));
}
```

### Guarda anche

* class [SnappyArchive](../../snappyarchive)
* spazio dei nomi [Aspose.Zip.Snappy](../../snappyarchive)
* assemblea [Aspose.Zip](../../../)

---

## Save(string) {#save_2}

Salva l'archivio scattante nel file di destinazione fornito.

```csharp
public void Save(string destinationFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destinationFileName | String | Il percorso dell'archivio da creare. Se il nome file specificato punta a un file esistente, verrà sovrascritto. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *destinationFileName* è zero. |
| SecurityException | Il chiamante non dispone dell'autorizzazione richiesta per accedere |
| ArgumentException | Il*destinationFileName* è vuoto, contiene solo spazi bianchi o contiene caratteri non validi. |
| UnauthorizedAccessException | Accesso al file*destinationFileName* è negato. |
| PathTooLongException | Il specificato*destinationFileName*, il nome del file o entrambi superano la lunghezza massima definita dal sistema. Ad esempio, sulle piattaforme basate su Windows, i percorsi devono essere inferiori a 248 caratteri e i nomi dei file devono essere inferiori a 260 caratteri. |
| NotSupportedException | Archivia a*destinationFileName* contiene due punti (:) al centro della stringa. |

### Esempi

```csharp
using (var archive = new SnappyArchive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save("result.snappy");
}
```

### Guarda anche

* class [SnappyArchive](../../snappyarchive)
* spazio dei nomi [Aspose.Zip.Snappy](../../snappyarchive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
