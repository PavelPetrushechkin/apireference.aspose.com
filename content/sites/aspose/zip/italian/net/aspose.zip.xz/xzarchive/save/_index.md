---
title: Save
second_title: Riferimento API Aspose.ZIP per .NET
description: Salva larchivio xz nello stream fornito.
type: docs
weight: 40
url: /it/net/aspose.zip.xz/xzarchive/save/
---
## Save(Stream) {#save}

Salva l'archivio xz nello stream fornito.

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
using (FileStream xzFile = File.Open("archive.xz", FileMode.Create))
{
    using (var archive = new XzArchive())
    {
        archive.SetSource("data.bin");
        archive.Save(xzFile);
     }
}
```

### Guarda anche

* class [XzArchive](../../xzarchive)
* spazio dei nomi [Aspose.Zip.Xz](../../xzarchive)
* assemblea [Aspose.Zip](../../../)

---

## Save(string) {#save_1}

Salva l'archivio xz nel file di destinazione fornito.

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
using (var archive = new XzArchive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save("result.xz");
}
```

### Guarda anche

* class [XzArchive](../../xzarchive)
* spazio dei nomi [Aspose.Zip.Xz](../../xzarchive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
