---
title: LzmaArchiveSettings
second_title: Aspose.ZIP für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonLzmaArchiveSettingsaspose.zip.lzma/lzmaarchivesettings Klasse mit Standardwörterbuchgröße entspricht 16 Megabyte.
type: docs
weight: 10
url: /de/net/aspose.zip.lzma/lzmaarchivesettings/lzmaarchivesettings/
---
## LzmaArchiveSettings constructor

Initialisiert eine neue Instanz von[`LzmaArchiveSettings`](../../lzmaarchivesettings) Klasse mit Standardwörterbuchgröße, entspricht 16 Megabyte.

```csharp
public LzmaArchiveSettings()
```

### Beispiele

```csharp
using (LzmaArchive archive = new LzmaArchive(new LzmaArchiveSettings() { DictionarySize = 1048576 } )
{
    archive.SetSource("data.bin);
    archive.Save(lzmaFile);
}
```

### Siehe auch

* class [LzmaArchiveSettings](../../lzmaarchivesettings)
* namensraum [Aspose.Zip.LZMA](../../lzmaarchivesettings)
* Montage [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
