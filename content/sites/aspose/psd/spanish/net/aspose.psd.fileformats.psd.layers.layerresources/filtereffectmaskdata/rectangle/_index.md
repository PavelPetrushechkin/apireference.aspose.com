---
title: Rectangle
second_title: Referencia de API de Aspose.PSD para .NET
description: Obtiene el rectángulo de los canales.
type: docs
weight: 80
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/
---
## FilterEffectMaskData.Rectangle property

Obtiene el rectángulo de los canales.

```csharp
public Rectangle Rectangle { get; }
```

### Ejemplos

Este ejemplo demuestra cómo obtener y establecer propiedades del recurso FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// comprobar después de guardar
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [FilterEffectMaskData](../../filtereffectmaskdata)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
