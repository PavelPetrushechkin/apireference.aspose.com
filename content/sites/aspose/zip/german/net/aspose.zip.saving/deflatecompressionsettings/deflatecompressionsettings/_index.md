---
title: DeflateCompressionSettings
second_title: Aspose.ZIP für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonDeflateCompressionSettingsaspose.zip.saving/deflatecompressionsettings Klasse.
type: docs
weight: 10
url: /de/net/aspose.zip.saving/deflatecompressionsettings/deflatecompressionsettings/
---
## DeflateCompressionSettings constructor

Initialisiert eine neue Instanz von[`DeflateCompressionSettings`](../../deflatecompressionsettings) Klasse.

```csharp
public DeflateCompressionSettings()
```

### Beispiele

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new DeflateCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");                   
    archive.Save(zipFile);
}
```

### Siehe auch

* class [DeflateCompressionSettings](../../deflatecompressionsettings)
* namensraum [Aspose.Zip.Saving](../../deflatecompressionsettings)
* Montage [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
