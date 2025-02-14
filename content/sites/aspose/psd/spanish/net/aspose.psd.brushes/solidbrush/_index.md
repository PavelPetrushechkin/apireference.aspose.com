---
title: SolidBrush
second_title: Referencia de API de Aspose.PSD para .NET
description: El pincel sólido está diseñado para dibujar continuamente con un color específico. Esta clase no se puede heredar.
type: docs
weight: 200
url: /es/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

El pincel sólido está diseñado para dibujar continuamente con un color específico. Esta clase no se puede heredar.

```csharp
public sealed class SolidBrush : Brush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SolidBrush](solidbrush#constructor)() | Inicializa una nueva instancia del[`SolidBrush`](../solidbrush) clase. |
| [SolidBrush](solidbrush#constructor_1)(Color) | Inicializa una nueva instancia del[`SolidBrush`](../solidbrush) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color) { get; set; } | Obtiene o establece el color del pincel. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor de 0 significa que el pincel es completamente visible, el valor de 1 significa que el pincel es completamente opaco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Crea un nuevo clon profundo del actual[`Brush`](../../aspose.psd/brush) . |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la imagen. Para demostrar la operación, el ejemplo crea una nueva imagen en formato PSD y dibuja formas primitivas en la superficie de la imagen utilizando los métodos de dibujo expuestos por la clase Graphics y luego la exporta al formato de archivo PSD.

```csharp
[C#]

//Crear una instancia de Imagen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crear e inicializar una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Borrar superficie gráfica
    graphics.Clear(Color.Wheat);

    // Dibuje un Arco especificando el objeto Pluma que tiene color Negro, 
    //un rectángulo que rodea el arco, el ángulo de inicio y el ángulo de barrido
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dibuje un Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dibuje una curva especificando el objeto Pen que tiene color verde y una matriz de puntos
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dibuja una Elipse usando el objeto Pluma y un Rectángulo circundante
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dibuja una línea 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dibujar un segmento circular
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dibuje un polígono especificando el objeto Pen que tiene color rojo y una matriz de puntos
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dibujar un Rectángulo
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Crear un objeto SolidBrush y establecer sus diversas propiedades
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dibuje una cadena usando el objeto SolidBrush y la fuente, en un punto específico
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Cree una instancia de PngOptions y configure sus diversas propiedades
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // guarda todos los cambios.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ver también

* class [Brush](../../aspose.psd/brush)
* espacio de nombres [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
