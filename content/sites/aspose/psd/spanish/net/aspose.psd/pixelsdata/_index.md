---
title: PixelsData
second_title: Referencia de API de Aspose.PSD para .NET
description: La clase para almacenar datos de píxeles de imagen y sus límites.
type: docs
weight: 5180
url: /es/net/aspose.psd/pixelsdata/
---
## PixelsData class

La clase para almacenar datos de píxeles de imagen y sus límites.

```csharp
public sealed class PixelsData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PixelsData](pixelsdata#constructor)() | Inicializa una nueva instancia del[`PixelsData`](../pixelsdata) clase. |
| [PixelsData](pixelsdata#constructor_1)(int[], Rectangle) | Inicializa una nueva instancia del[`PixelsData`](../pixelsdata) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds) { get; set; } | Obtiene o establece los límites de los datos de píxeles. |
| [Pixels](../../aspose.psd/pixelsdata/pixels) { get; set; } | Obtiene o establece los datos de píxeles. |

### Ejemplos

El siguiente código le muestra cómo crear un filtro inteligente personalizado que tiene un representador personalizado.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Inicia el filtro inteligente 'Crystallize' no compatible en la matriz de entrada
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // el ID del filtro inteligente 'Crystallize'.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Aplicar filtro a SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Aplicar filtro a la máscara de capa
        smartFilter.ApplyToMask(maskLayer);

        //Aplicar filtro a la capa
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // el ID del filtro inteligente 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // obtener la estructura del filtro
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // obtener el valor del tamaño de cristalización
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
