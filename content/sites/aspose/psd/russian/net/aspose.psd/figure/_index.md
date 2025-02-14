---
title: Figure
second_title: Справочник по Aspose.PSD для .NET API
description: Фигура. Контейнер для фигур.
type: docs
weight: 1200
url: /ru/net/aspose.psd/figure/
---
## Figure class

Фигура. Контейнер для фигур.

```csharp
public class Figure : ObjectWithBounds
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Figure](figure)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds) { get; } | Получает или устанавливает границы объекта. |
| [IsClosed](../../aspose.psd/figure/isclosed) { get; set; } | Получает или задает значение, указывающее, закрыта ли эта фигура. Замкнутая фигура будет иметь значение только в том случае, если формы первой и последней фигуры являются непрерывными фигурами. В этом случае первая точка первой фигуры будет соединена прямой линией с последней точкой последней фигуры. |
| [Segments](../../aspose.psd/figure/segments) { get; } | Получает все сегменты фигуры. |
| [Shapes](../../aspose.psd/figure/shapes) { get; } | Получает формы фигур. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape)(Shape) | Добавляет форму фигуре. |
| [AddShapes](../../aspose.psd/figure/addshapes)(Shape[]) | Добавляет к фигуре ряд фигур. |
| override [GetBounds](../../aspose.psd/figure/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd/figure/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [RemoveShape](../../aspose.psd/figure/removeshape)(Shape) | Удаляет фигуру с фигуры. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes)(Shape[]) | Удаляет диапазон фигур с фигуры. |
| [Reverse](../../aspose.psd/figure/reverse)() | Меняет порядок форм этой фигуры и порядок точек фигуры. |
| override [Transform](../../aspose.psd/figure/transform)(Matrix) | Применяет указанное преобразование к фигуре. |

### Примеры

В этих примерах используются GraphicsPath и класс Graphics для создания и управления рисунками на поверхности изображения. Пример создает новое изображение и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности. Наконец, изображение экспортируется в формат файла Tiff.

```csharp
[C#]

//Создаем экземпляр изображения 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем и инициализируем экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить графическую поверхность
    graphics.Clear(Color.Wheat);

    //Создаем экземпляр класса GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Создаем экземпляр класса Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Добавляем фигуры к объекту Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigure(figure);

    // Нарисовать путь с помощью объекта Pen черного цвета
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Создаем экземпляр TiffOptions и устанавливаем его различные свойства
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // сохранить все изменения.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Смотрите также

* class [ObjectWithBounds](../objectwithbounds)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
