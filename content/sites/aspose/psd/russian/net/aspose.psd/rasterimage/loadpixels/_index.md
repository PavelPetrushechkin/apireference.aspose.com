---
title: LoadPixels
second_title: Справочник по Aspose.PSD для .NET API
description: Загружает пиксели.
type: docs
weight: 400
url: /ru/net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Загружает пиксели.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | Rectangle | Прямоугольник, из которого загружаются пиксели. |

### Возвращаемое значение

Массив загруженных пикселей.

### Примеры

В этом примере показано, как загрузить информацию о пикселях в массив цвета типа, манипулировать массивом и установить его обратно в изображение. Для выполнения этих операций в этом примере создается новый файл изображения (в формате PSD) с использованием объекта MemoryStream.

```csharp
[C#]

//Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создаем экземпляр PsdOptions и устанавливаем его различные свойства, включая свойство Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Создаем экземпляр изображения
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Получить пиксели изображения, указав область в качестве границы изображения
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Цикл по массиву и установка цвета альтернативного индексированного пикселя
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Устанавливаем желтый цвет индексированного пикселя
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Устанавливаем синий цвет индексированного пикселя
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Применяем изменения пикселей к изображению
        image.SavePixels(image.Bounds, pixels);

        // сохранить все изменения.
        image.Save();
    }

    //Запись потока памяти в файл
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Смотрите также

* struct [Color](../../color)
* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* пространство имен [Aspose.PSD](../../rasterimage)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
