---
title: Rotate
second_title: Справочник по Aspose.PSD для .NET API
description: Повернуть изображение вокруг центра.
type: docs
weight: 610
url: /ru/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Повернуть изображение вокруг центра.

```csharp
public override void Rotate(float angle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | Single | Угол поворота в градусах. Положительные значения будут вращаться по часовой стрелке. |

### Примеры

Следующий код демонстрирует возможность поворота изображения на заданное значение угла.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Вращение всего изображения
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Вращение слоя
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Смотрите также

* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Повернуть изображение вокруг центра.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | Single | Угол поворота в градусах. Положительные значения будут вращаться по часовой стрелке. |
| resizeProportionally | Boolean | если установлено`истинный` у вас будет размер вашего изображения, измененный в соответствии с проекциями повернутого прямоугольника (угловые точки), в другом случае, который оставляет размеры нетронутыми, и поворачивается только внутреннее содержимое изображения. |
| backgroundColor | Color | Цвет фона. |

### Смотрите также

* struct [Color](../../../aspose.psd/color)
* class [PsdImage](../../psdimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
