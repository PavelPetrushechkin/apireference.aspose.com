---
title: Bzip2CompressionSettings
second_title: Aspose.ZIP для справочника API .NET
description: Инициализирует новый экземплярBzip2CompressionSettingsaspose.zip.saving/bzip2compressionsettings класс.
type: docs
weight: 10
url: /ru/net/aspose.zip.saving/bzip2compressionsettings/bzip2compressionsettings/
---
## Bzip2CompressionSettings(int) {#constructor_1}

Инициализирует новый экземпляр[`Bzip2CompressionSettings`](../../bzip2compressionsettings) класс.

```csharp
public Bzip2CompressionSettings(int blockSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| blockSize | Int32 | Размер блока в сотнях килобайт. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Размер блока не находится между 1 и 9. |

### Примеры

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new Bzip2CompressionSettings(1))))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Смотрите также

* class [Bzip2CompressionSettings](../../bzip2compressionsettings)
* пространство имен [Aspose.Zip.Saving](../../bzip2compressionsettings)
* сборка [Aspose.Zip](../../../)

---

## Bzip2CompressionSettings() {#constructor}

Инициализирует новый экземпляр[`Bzip2CompressionSettings`](../../bzip2compressionsettings)класс с размером блока по умолчанию, равным 9 сотням килобайт.

```csharp
public Bzip2CompressionSettings()
```

### Примеры

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new Bzip2CompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Смотрите также

* class [Bzip2CompressionSettings](../../bzip2compressionsettings)
* пространство имен [Aspose.Zip.Saving](../../bzip2compressionsettings)
* сборка [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
