---
title: LayerEffectsTypes
second_title: Referencia de API de Aspose.PSD para .NET
description: Efectos de fusión de capas
type: docs
weight: 2640
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Efectos de fusión de capas

```csharp
public enum LayerEffectsTypes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| DropShadow | `0` | La sombra paralela |
| OuterGlow | `1` | El resplandor exterior |
| PatternOverlay | `2` | El patrón superpuesto |
| GradientOverlay | `3` | La superposición de degradado |
| ColorOverlay | `4` | La superposición de color |
| Satin | `5` | El tipo de efecto satinado |
| InnerGlow | `6` | El resplandor interior |
| InnerShadow | `7` | La sombra interior |
| Stroke | `8` | El trazo |
| BevelEmboss | `9` | El bisel en relieve |

### Ejemplos

El siguiente código demuestra la compatibilidad con la propiedad ILayerEffect.EffectType.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // atrapó
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
