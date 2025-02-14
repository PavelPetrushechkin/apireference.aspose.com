---
title: AddNoiseSmartFilter
second_title: Referencia de API de Aspose.PSD para .NET
description: El filtro inteligente AddNoise.
type: docs
weight: 3360
url: /es/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---
## AddNoiseSmartFilter class

El filtro inteligente AddNoise.

```csharp
public sealed class AddNoiseSmartFilter : SmartFilter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AddNoiseSmartFilter](addnoisesmartfilter)() | Inicializa una nueva instancia del[`AddNoiseSmartFilter`](../addnoisesmartfilter) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AmountNoise](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/amountnoise) { get; set; } | Obtiene o establece la cantidad del valor de ruido. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode) { get; set; } | Obtiene o establece el modo de fusión. |
| [Distribution](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution) { get; set; } | Obtiene o establece la distribución del filtro de ruido. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filterid) { get; } | Obtiene el identificador del tipo de filtro inteligente. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled) { get; set; } | Obtiene o establece el estado habilitado del filtro inteligente. |
| [IsMonochromatic](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/ismonochromatic) { get; set; } | Obtiene o establece el valor de monocromático. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/name) { get; } | Obtiene el nombre del filtro inteligente. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity) { get; set; } | Obtiene o establece el valor de opacidad del filtro inteligente. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor) { get; } | La estructura del descriptor de origen con datos de filtro inteligente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply)(RasterImage) | Aplica el filtro actual a la entrada[`RasterImage`](../../aspose.psd/rasterimage) imagen. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask)(Layer) | Aplica el filtro actual a la entrada[`Layer`](../../aspose.psd.fileformats.psd.layers/layer) enmascarar datos. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone)() | Hace el clon miembro de la instancia actual del tipo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filtertype) | El identificador del filtro inteligente actual. |

### Ejemplos

Este ejemplo demuestra el soporte de la interfaz de filtros inteligentes.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // editar filtros inteligentes
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // comprobar los valores del filtro
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // actualizar los valores del filtro
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // agregar nuevos elementos de filtro
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // aplicar los cambios
    smartObj.SmartFilters.UpdateResourceValues();

    // Aplicar filtros
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // comprobar los valores del filtro
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Ver también

* class [SmartFilter](../smartfilter)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
