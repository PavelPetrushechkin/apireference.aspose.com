---
title: LzmaCompressionSettings
second_title: Aspose.ZIP لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفLzmaCompressionSettingsaspose.zip.saving/lzmacompressionsettings فئة بحجم القاموس الافتراضي  تساوي 16 ميغا بايت.
type: docs
weight: 10
url: /ar/net/aspose.zip.saving/lzmacompressionsettings/lzmacompressionsettings/
---
## LzmaCompressionSettings constructor

يقوم بتهيئة مثيل جديد لملف[`LzmaCompressionSettings`](../../lzmacompressionsettings) فئة بحجم القاموس الافتراضي ، تساوي 16 ميغا بايت.

```csharp
public LzmaCompressionSettings()
```

### أمثلة

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new LzmaCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### أنظر أيضا

* class [LzmaCompressionSettings](../../lzmacompressionsettings)
* مساحة الاسم [Aspose.Zip.Saving](../../lzmacompressionsettings)
* المجسم [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
