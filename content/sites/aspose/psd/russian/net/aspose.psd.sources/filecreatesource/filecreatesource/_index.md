---
title: FileCreateSource
second_title: Справочник по Aspose.PSD для .NET API
description: Инициализирует новый экземплярFileCreateSourceaspose.psd.sources/filecreatesource класс.
type: docs
weight: 10
url: /ru/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Инициализирует новый экземпляр[`FileCreateSource`](../../filecreatesource) класс.

```csharp
public FileCreateSource(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для создания. |

### Примеры

В этом примере создается новый файл изображения в некотором месте на диске, как указано в свойстве Source экземпляра BmpOptions. Если второй параметр не передан конструктору FileCreateSource, то по умолчанию создаваемый файл имеет свойство IsTemporal, установленное в True. Если для параметра IsTemporal задано значение True, в конце выполнения ни один файл не будет сохранен на диске.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Создает экземпляр PsdOptions и устанавливает его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра PsdOptions
//Если второй параметр не передан, то по умолчанию для файла IsTemporal установлено значение True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

// Создает экземпляр изображения 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // делаем некоторую обработку изображения
}
```

### Смотрите также

* class [FileCreateSource](../../filecreatesource)
* пространство имен [Aspose.PSD.Sources](../../filecreatesource)
* сборка [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Инициализирует новый экземпляр[`FileCreateSource`](../../filecreatesource) класс.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для создания. |
| isTemporal | Boolean | Если установлено`истинный` созданный файл будет временным. |

### Примеры

В этом примере создается новый файл изображения в некотором месте на диске, как указано в свойстве Source экземпляра PsdOptions. Несколько свойств экземпляра PsdOptions задаются перед созданием фактического образа. Особенно свойство Source, которое в данном случае относится к фактическому местоположению на диске.

```csharp
[C#]

//Создаем экземпляр PsdOptions и устанавливаем его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра PsdOptions
//Второй логический параметр определяет, является ли создаваемый файл временным или нет
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Создаем экземпляр Image и инициализируем его экземпляром PsdOptions, вызвав метод Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // делаем некоторую обработку изображения

    // сохранить все изменения
    image.Save();
}
```

### Смотрите также

* class [FileCreateSource](../../filecreatesource)
* пространство имен [Aspose.PSD.Sources](../../filecreatesource)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
