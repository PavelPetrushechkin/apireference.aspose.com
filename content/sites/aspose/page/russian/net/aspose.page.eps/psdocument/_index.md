---
title: PsDocument
second_title: Справочник по Aspose.Page для .NET API
description: Этот класс инкапсулирует документы PS/EPS.
type: docs
weight: 100
url: /ru/net/aspose.page.eps/psdocument/
---
## PsDocument class

Этот класс инкапсулирует документы PS/EPS.

```csharp
public sealed class PsDocument : Document
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsDocument](psdocument)(Stream) | Инициализирует[`PsDocument`](../psdocument) с потоком файла PS/EPS. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [NumberOfPages](../../aspose.page.eps/psdocument/numberofpages) { get; } | Возвращает количество страниц в результирующем документе PDF. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetXmpMetadata](../../aspose.page.eps/psdocument/getxmpmetadata)() | Читает файл PS/EPS и извлекает XmpMetdata, если он уже существует, или добавляет новый, если он не существует. |
| [Merge](../../aspose.page.eps/psdocument/merge)(string[], Device, SaveOptions) | Слияние файлов PS/EPS на устройство. |
| [Save](../../aspose.page.eps/psdocument/save#save_1)(Stream) | сохранено[`PsDocument`](../psdocument) как EPS-файл. Этот метод используется только после обновления метаданных XMP. Он сохраняет исходный файл EPS с обновленными существующими метаданными или новым, созданным при вызове метода GetMetadata. В последнем случае добавляется весь необходимый код PostScript и комментарии EPS. |
| override [Save](../../aspose.page.eps/psdocument/save#save)(Device, SaveOptions) | Сохраняет файл PS/EPS на устройство. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps)(Bitmap, Stream, PsSaveOptions) | Сохраняет объект Bitmap в выходной поток EPS. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_1)(Bitmap, string, PsSaveOptions) | Сохраняет объект Bitmap в файл EPS. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_2)(Stream, Stream, PsSaveOptions) | Сохраняет изображение PNG/JPEG/TIFF/BMP/GIF/EMF из входного потока в выходной поток EPS. |
| static [SaveImageAsEps](../../aspose.page.eps/psdocument/saveimageaseps#saveimageaseps_3)(string, string, PsSaveOptions) | Сохраняет изображение PNG/JPEG/TIFF/BMP/GIF/EMF из файла в файл EPS. |

### Смотрите также

* class [Document](../../aspose.page/document)
* пространство имен [Aspose.Page.EPS](../../aspose.page.eps)
* сборка [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
