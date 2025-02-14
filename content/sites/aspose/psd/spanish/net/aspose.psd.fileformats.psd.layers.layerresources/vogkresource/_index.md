---
title: VogkResource
second_title: Referencia de API de Aspose.PSD para .NET
description: El recurso de datos de origen vectorial.
type: docs
weight: 3310
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

El recurso de datos de origen vectorial.

```csharp
public sealed class VogkResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VogkResource](vogkresource)() | Inicializa una nueva instancia del[`VogkResource`](../vogkresource) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion) { get; } | Obtiene la versión psd mínima necesaria para el recurso de capa. 0 indica que no hay restricciones. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings) { get; set; } | Obtiene o establece la configuración del origen de la forma. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature) { get; } | Obtiene la firma del recurso de la capa. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version) { get; set; } | Obtiene o establece la versión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey) | La clave de información de la herramienta de tipo. |

### Ejemplos

El siguiente ejemplo demuestra el soporte del recurso VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Lectura
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Edición
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
