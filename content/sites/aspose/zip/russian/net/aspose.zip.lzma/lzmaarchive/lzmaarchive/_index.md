---
title: LzmaArchive
second_title: Aspose.ZIP для справочника API .NET
description: Инициализирует новый экземплярLzmaArchiveaspose.zip.lzma/lzmaarchive class и составляет архив в формате lzma.
type: docs
weight: 10
url: /ru/net/aspose.zip.lzma/lzmaarchive/lzmaarchive/
---
## LzmaArchive(LzmaArchiveSettings) {#constructor}

Инициализирует новый экземпляр[`LzmaArchive`](../../lzmaarchive) class и составляет архив в формате lzma.

```csharp
public LzmaArchive(LzmaArchiveSettings settings = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | LzmaArchiveSettings | Набор настроек конкретного архива lzma. |

### Смотрите также

* class [LzmaArchiveSettings](../../lzmaarchivesettings)
* class [LzmaArchive](../../lzmaarchive)
* пространство имен [Aspose.Zip.LZMA](../../lzmaarchive)
* сборка [Aspose.Zip](../../../)

---

## LzmaArchive(Stream) {#constructor_1}

Инициализирует новый экземпляр[`LzmaArchive`](../../lzmaarchive) класс подготовлен к распаковке.

```csharp
public LzmaArchive(Stream source)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Stream | Источник архива. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | *source* не доступен для поиска. |
| ArgumentNullException | *source* нулевой. |

### Примечания

Этот конструктор не распаковывается. Видеть[`Extract`](../extract) метод распаковки.

### Смотрите также

* class [LzmaArchive](../../lzmaarchive)
* пространство имен [Aspose.Zip.LZMA](../../lzmaarchive)
* сборка [Aspose.Zip](../../../)

---

## LzmaArchive(string) {#constructor_2}

Инициализирует новый экземпляр[`LzmaArchive`](../../lzmaarchive) класс подготовлен к распаковке.

```csharp
public LzmaArchive(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к источнику архива. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *path* нулевой. |
| SecurityException | У вызывающего абонента нет необходимого разрешения для доступа |
| ArgumentException | *path* пуст, содержит только пробелы или содержит недопустимые символы. |
| UnauthorizedAccessException | Доступ к файлу*path* отказано. |
| PathTooLongException | Указанный*path*, имя файла или оба превышают максимальную длину, определенную системой. Например, на платформах Windows пути должны содержать менее 248 символов, а имена файлов — менее 260 символов. |
| NotSupportedException | Файл в*path* содержит двоеточие (:) в середине строки. |

### Примечания

Этот конструктор не распаковывается. Видеть[`Extract`](../extract) метод распаковки.

### Примеры

```csharp
using (FileStream extractedFile = File.Open(extractedFileName, FileMode.Create))
{
    using (var archive = new LzmaArchive(sourceLzmaFile))
    {
         archive.Extract(extractedFile);
    }
   }
```

### Смотрите также

* class [LzmaArchive](../../lzmaarchive)
* пространство имен [Aspose.Zip.LZMA](../../lzmaarchive)
* сборка [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
