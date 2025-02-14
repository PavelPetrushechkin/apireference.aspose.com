---
title: Extract
second_title: Aspose.ZIP für .NET-API-Referenz
description: Extrahiert das ZArchiv in einen Stream.
type: docs
weight: 30
url: /de/net/aspose.zip.z/zarchive/extract/
---
## Extract(Stream) {#extract_1}

Extrahiert das Z-Archiv in einen Stream.

```csharp
public void Extract(Stream destination)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destination | Stream | Stream zum Speichern dekomprimierter Daten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidDataException | Daten können nicht dekomprimiert werden. |

### Beispiele

```csharp
using (FileStream zFile = File.Open(sourceFileName, FileMode.Open))
{
    using (FileStream extractedFile = File.Open(extractedFileName, FileMode.Create))
    {
        using (var archive = new ZArchive(zFile))
        {
            archive.Extract(extractedFile);
        }
    }
}
```

### Siehe auch

* class [ZArchive](../../zarchive)
* namensraum [Aspose.Zip.Z](../../zarchive)
* Montage [Aspose.Zip](../../../)

---

## Extract(FileInfo) {#extract}

Extrahiert das Z-Archiv in eine Datei.

```csharp
public void Extract(FileInfo fileInfo)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileInfo | FileInfo | FileInfo zum Speichern dekomprimierter Daten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| SecurityException | Der Anrufer hat nicht die erforderliche Berechtigung zum Öffnen der*fileInfo*. |
| ArgumentException | Dateipfad ist leer oder enthält nur Leerzeichen. |
| FileNotFoundException | Die Datei wird nicht gefunden. |
| UnauthorizedAccessException | Pfad zur Datei ist schreibgeschützt oder ist ein Verzeichnis. |
| ArgumentNullException | *fileInfo* ist Null. |
| DirectoryNotFoundException | Der angegebene Pfad ist ungültig, da er sich beispielsweise auf einem nicht zugeordneten Laufwerk befindet. |
| IOException | Die Datei ist bereits geöffnet. |
| InvalidDataException | Daten können nicht dekomprimiert werden. |

### Beispiele

```csharp
using (FileStream zFile = File.Open(sourceFileName, FileMode.Open))
{
    using (var archive = new ZArchive(zFile))
    {
        archive.Extract(new FileInfo("extracted.bin"));
    }
}
```

### Siehe auch

* class [ZArchive](../../zarchive)
* namensraum [Aspose.Zip.Z](../../zarchive)
* Montage [Aspose.Zip](../../../)

---

## Extract(string) {#extract_2}

Extrahiert das Z-Archiv nach Pfad in eine Datei.

```csharp
public void Extract(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Pfad zur Datei, in der dekomprimierte Daten gespeichert werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *path* ist Null. |
| SecurityException | Der Anrufer verfügt nicht über die erforderliche Zugriffsberechtigung |
| ArgumentException | Das*path* leer ist, nur Leerzeichen enthält oder ungültige Zeichen enthält. |
| UnauthorizedAccessException | Zugriff auf Datei*path* ist abgelehnt. |
| PathTooLongException | Die angegebene*path*, Dateiname oder beide überschreiten die vom System definierte maximale Länge. Beispielsweise müssen auf Windows-basierten Plattformen Pfade weniger als 248 Zeichen und Dateinamen weniger als 260 Zeichen umfassen. |
| NotSupportedException | Datei unter*path* enthält einen Doppelpunkt (:) in der Mitte der Zeichenfolge. |
| InvalidDataException | Daten können nicht dekomprimiert werden. |

### Beispiele

```csharp
using (FileStream zFile = File.Open(sourceFileName, FileMode.Open))
{
    using (var archive = new ZArchive(zFile))
    {
        archive.Extract("extracted.bin");
    }
}
```

### Siehe auch

* class [ZArchive](../../zarchive)
* namensraum [Aspose.Zip.Z](../../zarchive)
* Montage [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
