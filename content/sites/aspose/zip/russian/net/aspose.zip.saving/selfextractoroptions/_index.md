---
title: SelfExtractorOptions
second_title: Aspose.ZIP для справочника API .NET
description: Параметры создания самораспаковывающегося исполняемого архива.
type: docs
weight: 430
url: /ru/net/aspose.zip.saving/selfextractoroptions/
---
## SelfExtractorOptions class

Параметры создания самораспаковывающегося исполняемого архива.

```csharp
public class SelfExtractorOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SelfExtractorOptions](selfextractoroptions)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CloseWindowOnExtraction](../../aspose.zip.saving/selfextractoroptions/closewindowonextraction) { get; set; } | Получает или задает значение, указывающее, должно ли окно экстрактора закрываться при извлечении или нет. |
| [ExtractorTitle](../../aspose.zip.saving/selfextractoroptions/extractortitle) { get; set; } | Получает или устанавливает заголовок окна экстрактора. |
| [RunAfterExtraction](../../aspose.zip.saving/selfextractoroptions/runafterextraction) { get; set; } | Получает или задает программу, которая будет выполняться после завершения извлечения архива. |
| [TitleIcon](../../aspose.zip.saving/selfextractoroptions/titleicon) { get; set; } | Получает или задает путь к значку заголовка для главных окон приложения экстрактора. |

### Примечания

Самораспаковывающийся архив нельзя составить с лимитной лицензией:[`MeteredLicense`](../../aspose.zip/meteredlicense) .

### Примеры

```csharp
using (FileStream zipFile = File.Open("archive.exe", FileMode.Create))
{
    using (var archive = new Archive())
    {
        archive.CreateEntry("entry.bin", "data.bin");
        var sfxOptions = new SelfExtractorOptions() { ExtractorTitle = "Extractor", CloseWindowOnExtraction = true, TitleIcon = "C:\pictorgam.ico" };
        archive.Save(zipFile, new ArchiveSaveOptions() { SelfExtractorOptions = sfxOptions });
    }
}
```

### Смотрите также

* пространство имен [Aspose.Zip.Saving](../../aspose.zip.saving)
* сборка [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
