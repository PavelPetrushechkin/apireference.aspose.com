---
title: Bzip2CompressionSettings
second_title: Aspose.ZIP för .NET API-referens
description: Initierar en ny instans avBzip2CompressionSettingsaspose.zip.saving/bzip2compressionsettings class.
type: docs
weight: 10
url: /sv/net/aspose.zip.saving/bzip2compressionsettings/bzip2compressionsettings/
---
## Bzip2CompressionSettings(int) {#constructor_1}

Initierar en ny instans av[`Bzip2CompressionSettings`](../../bzip2compressionsettings) class.

```csharp
public Bzip2CompressionSettings(int blockSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| blockSize | Int32 | Blockstorlek i hundratals kilobyte. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | Blockstorleken är inte mellan 1 och 9. |

### Exempel

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new Bzip2CompressionSettings(1))))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Se även

* class [Bzip2CompressionSettings](../../bzip2compressionsettings)
* namnutrymme [Aspose.Zip.Saving](../../bzip2compressionsettings)
* hopsättning [Aspose.Zip](../../../)

---

## Bzip2CompressionSettings() {#constructor}

Initierar en ny instans av[`Bzip2CompressionSettings`](../../bzip2compressionsettings)klass med standardblockstorlek, lika med 9 hundra kilobyte.

```csharp
public Bzip2CompressionSettings()
```

### Exempel

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new Bzip2CompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Se även

* class [Bzip2CompressionSettings](../../bzip2compressionsettings)
* namnutrymme [Aspose.Zip.Saving](../../bzip2compressionsettings)
* hopsättning [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
