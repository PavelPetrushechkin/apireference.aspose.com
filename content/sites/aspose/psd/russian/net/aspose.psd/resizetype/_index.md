---
title: ResizeType
second_title: Справочник по Aspose.PSD для .NET API
description: Определяет тип изменения размера.
type: docs
weight: 5300
url: /ru/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Определяет тип изменения размера.

```csharp
public enum ResizeType
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| None | `0` | Пиксели не сохраняются во время операции изменения размера. |
| LeftTopToLeftTop | `1` | Левая верхняя точка нового изображения совпадет с левой верхней точкой исходного изображения. При необходимости произойдет кадрирование. |
| RightTopToRightTop | `2` | Правая верхняя точка нового изображения совпадет с правой верхней точкой исходного изображения. При необходимости произойдет кадрирование. |
| RightBottomToRightBottom | `3` | Правая нижняя точка нового изображения совпадет с правой нижней точкой исходного изображения. При необходимости произойдет кадрирование. |
| LeftBottomToLeftBottom | `4` | Левая нижняя точка нового изображения будет совпадать с левой нижней точкой исходного изображения. При необходимости произойдет кадрирование. |
| CenterToCenter | `5` | Центр нового изображения совпадет с центром исходного изображения. При необходимости произойдет кадрирование. |
| LanczosResample | `6` | Повторная выборка с использованием алгоритма Ланцоша с a=3. |
| NearestNeighbourResample | `7` | Передискретизировать с использованием алгоритма ближайшего соседа. |
| AdaptiveResample | `8` | Повторная выборка с использованием адаптивного алгоритма на основе взвешенной и смешанной рациональной функции и алгоритмов интерполяции lanczos3. |
| BilinearResample | `9` | Повторная выборка с использованием билинейной интерполяции. Предварительная фильтрация изображения разрешена для удаления шума перед повторной выборкой, когда это необходимо |
| HighQualityResample | `10` | Высококачественный ресемпл |
| CatmullRom | `11` | Метод кубической интерполяции Катмулла-Рома. |
| CubicConvolution | `12` | Метод интерполяции кубической свертки |
| CubicBSpline | `13` | Метод кубической интерполяции CubicBSpline |
| Mitchell | `14` | Метод кубической интерполяции Митчелла |
| SinC | `15` | Метод кубической интерполяции Sinc (Lanczos3) |
| Bell | `16` | Метод интерполяции Белла |

### Примеры

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

В следующем коде показано, как изменить размер изображения с помощью нового типа изменения размера CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
