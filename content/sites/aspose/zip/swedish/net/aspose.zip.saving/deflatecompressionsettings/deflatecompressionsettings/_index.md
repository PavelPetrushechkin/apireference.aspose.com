---
title: DeflateCompressionSettings
second_title: Aspose.ZIP för .NET API-referens
description: Initierar en ny instans avDeflateCompressionSettingsaspose.zip.saving/deflatecompressionsettings class.
type: docs
weight: 10
url: /sv/net/aspose.zip.saving/deflatecompressionsettings/deflatecompressionsettings/
---
## DeflateCompressionSettings constructor

Initierar en ny instans av[`DeflateCompressionSettings`](../../deflatecompressionsettings) class.

```csharp
public DeflateCompressionSettings()
```

### Exempel

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new DeflateCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");                   
    archive.Save(zipFile);
}
```

### Se även

* class [DeflateCompressionSettings](../../deflatecompressionsettings)
* namnutrymme [Aspose.Zip.Saving](../../deflatecompressionsettings)
* hopsättning [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
