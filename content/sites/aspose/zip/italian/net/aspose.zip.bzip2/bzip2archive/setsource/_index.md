---
title: SetSource
second_title: Riferimento API Aspose.ZIP per .NET
description: Imposta il contenuto da comprimere allinterno dellarchivio.
type: docs
weight: 60
url: /it/net/aspose.zip.bzip2/bzip2archive/setsource/
---
## SetSource(Stream) {#setsource_3}

Imposta il contenuto da comprimere all'interno dell'archivio.

```csharp
public void SetSource(Stream source)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | Stream | Il flusso di input per l'archivio. |

### Esempi

```csharp
using (Bzip2Archive archive = new Bzip2Archive()) 
{
    archive.SetSource(new MemoryStream(new byte[] { 0x00,0xFF }));
    archive.Save("archive.bz2");
}
```

### Guarda anche

* class [Bzip2Archive](../../bzip2archive)
* spazio dei nomi [Aspose.Zip.Bzip2](../../bzip2archive)
* assemblea [Aspose.Zip](../../../)

---

## SetSource(FileInfo) {#setsource_2}

Imposta il contenuto da comprimere all'interno dell'archivio.

```csharp
public void SetSource(FileInfo fileInfo)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileInfo | FileInfo | Il riferimento a un file da comprimere. |

### Esempi

```csharp
using (Bzip2Archive archive = new Bzip2Archive()) 
{
    archive.SetSource(new FileInfo("data.bin"));
    archive.Save("archive.bz2");
}
```

### Guarda anche

* class [Bzip2Archive](../../bzip2archive)
* spazio dei nomi [Aspose.Zip.Bzip2](../../bzip2archive)
* assemblea [Aspose.Zip](../../../)

---

## SetSource(string) {#setsource_4}

Imposta il contenuto da comprimere all'interno dell'archivio.

```csharp
public void SetSource(string path)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Percorso del file da comprimere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *path* è zero. |
| SecurityException | Il chiamante non dispone dell'autorizzazione richiesta per accedere |
| ArgumentException | Il*path* è vuoto, contiene solo spazi bianchi o contiene caratteri non validi. |
| UnauthorizedAccessException | Accesso al file*path* è negato. |
| PathTooLongException | Il specificato*path*, il nome del file o entrambi superano la lunghezza massima definita dal sistema. Ad esempio, sulle piattaforme basate su Windows, i percorsi devono essere inferiori a 248 caratteri e i nomi dei file devono essere inferiori a 260 caratteri. |
| NotSupportedException | Archivia a*path* contiene due punti (:) al centro della stringa. |

### Esempi

```csharp
using (Bzip2Archive archive = new Bzip2Archive()) 
{
    archive.SetSource("data.bin");
    archive.Save("archive.bz2");
}
```

### Guarda anche

* class [Bzip2Archive](../../bzip2archive)
* spazio dei nomi [Aspose.Zip.Bzip2](../../bzip2archive)
* assemblea [Aspose.Zip](../../../)

---

## SetSource(TarArchive, TarFormat) {#setsource_1}

Imposta il contenuto da comprimere all'interno dell'archivio.

```csharp
public void SetSource(TarArchive tarArchive, TarFormat format = TarFormat.UsTar)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tarArchive | TarArchive | Archivio Tar da comprimere. |
| format | TarFormat | Definisce il formato dell'intestazione tar. |

### Osservazioni

Utilizzare questo metodo per comporre un archivio tar.bz2 congiunto.

### Esempi

```csharp
using (var tarArchive = new TarArchive())
{
    tarArchive.CreateEntry("first.bin", "data1.bin");
    tarArchive.CreateEntry("second.bin", "data2.bin");
    using (var bzippedArchive = new Bzip2Archive())
    {
        bzippedArchive.SetSource(tarArchive);
        bzippedArchive.Save("archive.tar.bz2");
    }
}
```

### Guarda anche

* class [TarArchive](../../../aspose.zip.tar/tararchive)
* enum [TarFormat](../../../aspose.zip.tar/tarformat)
* class [Bzip2Archive](../../bzip2archive)
* spazio dei nomi [Aspose.Zip.Bzip2](../../bzip2archive)
* assemblea [Aspose.Zip](../../../)

---

## SetSource(CpioArchive, CpioFormat) {#setsource}

Imposta il contenuto da comprimere all'interno dell'archivio.

```csharp
public void SetSource(CpioArchive cpioArchive, CpioFormat format = CpioFormat.OldAscii)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cpioArchive | CpioArchive | Archivio Cpio da comprimere. |
| format | CpioFormat | Definisce il formato dell'intestazione cpio. |

### Osservazioni

Utilizzare questo metodo per comporre un archivio cpio.bz2 congiunto.

### Esempi

```csharp
using (var cpioArchive = new CpioArchive())
{
    cpioArchive.CreateEntry("first.bin", "data1.bin");
    cpioArchive.CreateEntry("second.bin", "data2.bin");
    using (var bzippedArchive = new Bzip2Archive())
    {
        bzippedArchive.SetSource(cpioArchive);
        bzippedArchive.Save("archive.cpio.bz2");
    }
}
```

### Guarda anche

* class [CpioArchive](../../../aspose.zip.cpio/cpioarchive)
* enum [CpioFormat](../../../aspose.zip.cpio/cpioformat)
* class [Bzip2Archive](../../bzip2archive)
* spazio dei nomi [Aspose.Zip.Bzip2](../../bzip2archive)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
