---
title: XzBcjX86FilterSettings
second_title: Aspose.ZIP для справочника API .NET
description: Инициализирует новый экземплярXzBcjX86FilterSettingsaspose.zip.xz.settings/xzbcjx86filtersettings . Используйте его для сжатия исполняемых файлов и библиотек внутриXzArchiveaspose.zip.xz/xzarchive .
type: docs
weight: 10
url: /ru/net/aspose.zip.xz.settings/xzbcjx86filtersettings/xzbcjx86filtersettings/
---
## XzBcjX86FilterSettings constructor

Инициализирует новый экземпляр[`XzBcjX86FilterSettings`](../../xzbcjx86filtersettings) . Используйте его для сжатия исполняемых файлов и библиотек внутри[`XzArchive`](../../../aspose.zip.xz/xzarchive) .

```csharp
public XzBcjX86FilterSettings()
```

### Примеры

```csharp
XzLZMA2FilterSettings lzma2 = new XzLZMA2FilterSettings(5242880);
XzBcjX86FilterSettings bcj = new XzBcjX86FilterSettings();
XzArchiveSettings settings = new XzArchiveSettings(new XzFilterSettings[] {bcj,lzma2}, 10485760, XzCheckType.Crc32);
using (XzArchive archive = new XzArchive(settings))
{
    archive.SetSource("data.bin");
    archive.Save("archive.xz");
}
```

### Смотрите также

* class [XzBcjX86FilterSettings](../../xzbcjx86filtersettings)
* пространство имен [Aspose.Zip.Xz.Settings](../../xzbcjx86filtersettings)
* сборка [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
