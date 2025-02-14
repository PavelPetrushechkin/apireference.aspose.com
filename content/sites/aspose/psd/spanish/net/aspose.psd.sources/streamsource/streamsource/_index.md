---
title: StreamSource
second_title: Referencia de API de Aspose.PSD para .NET
description: Inicializa una nueva instancia delStreamSourceaspose.psd.sources/streamsource clase.
type: docs
weight: 10
url: /es/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Inicializa una nueva instancia del[`StreamSource`](../../streamsource) clase.

```csharp
public StreamSource(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente para abrir. |

### Ejemplos

Este ejemplo muestra cómo cargar información de píxeles en una matriz de color de tipo, manipular la matriz y volver a establecerla en la imagen. Para realizar estas operaciones, este ejemplo crea un nuevo archivo de imagen (en formato PSD) utilizando el objeto MemoryStream.

```csharp
[C#]

//Crear una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Cree una instancia de PsdOptions y establezca sus diversas propiedades, incluida la propiedad Fuente
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Crear una instancia de Imagen
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Obtenga los píxeles de la imagen especificando el área como límite de la imagen
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Recorre la matriz y establece el color del píxel indexado alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Establecer el color del píxel indexado en amarillo
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Establecer el color del píxel indexado en azul
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Aplicar los cambios de píxel a la imagen
        image.SavePixels(image.Bounds, pixels);

        // guarda todos los cambios.
        image.Save();
    }

    //Escribir flujo de memoria en archivo
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ver también

* class [StreamSource](../../streamsource)
* espacio de nombres [Aspose.PSD.Sources](../../streamsource)
* asamblea [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Inicializa una nueva instancia del[`StreamSource`](../../streamsource) clase.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente para abrir. |
| disposeStream | Boolean | si se establece en`verdadero` la corriente será eliminada. |

### Ejemplos

Este ejemplo demuestra el uso de System.IO.Stream para crear un nuevo archivo de imagen

```csharp
[C#]

//Crea una instancia de PsdOptions y establece sus diversas propiedades
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crear una instancia de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definir la propiedad de origen para la instancia de PsdOptions
//El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea una instancia de Image y llama al método Create con PsdOptions como parámetro para inicializar el objeto Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //hacer un poco de procesamiento de imagen
}
```

### Ver también

* class [StreamSource](../../streamsource)
* espacio de nombres [Aspose.PSD.Sources](../../streamsource)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
