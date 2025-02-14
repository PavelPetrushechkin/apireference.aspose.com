---
title: Open
second_title: Riferimento API Aspose.ZIP per .NET
description: Apre larchivio per lestrazione e fornisce uno stream con il contenuto dellarchivio.
type: docs
weight: 50
url: /it/net/aspose.zip.gzip/gziparchive/open/
---
## GzipArchive.Open method

Apre l'archivio per l'estrazione e fornisce uno stream con il contenuto dell'archivio.

```csharp
public Stream Open()
```

### Valore di ritorno

Il flusso che rappresenta il contenuto dell'archivio.

### Osservazioni

Leggi dal flusso per ottenere il contenuto originale del file. Vedere la sezione esempi.

### Esempi

Estrae l'archivio e copia il contenuto estratto nel flusso di file.

È possibile utilizzare il metodo Stream.CopyTo per .NET 4.0 e versioni successive:

```csharp
unpacked.CopyTo(extracted);
```

```csharp
using (var archive = new GzipArchive("archive.gz"))
{
    using (var extracted = File.Create("data.bin"))
    {
        var unpacked = archive.Open();
        byte[] b = new byte[8192];
        int bytesRead;
        while (0 < (bytesRead = unpacked.Read(b, 0, b.Length)))
            extracted.Write(b, 0, bytesRead);
    }            
}
```

### Guarda anche

* class [GzipArchive](../../gziparchive)
* spazio dei nomi [Aspose.Zip.Gzip](../../gziparchive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
