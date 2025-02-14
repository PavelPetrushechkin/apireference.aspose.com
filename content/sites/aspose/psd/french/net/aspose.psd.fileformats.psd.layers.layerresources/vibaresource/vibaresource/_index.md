---
title: VibAResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Initialise une nouvelle instance duVibAResourceaspose.psd.fileformats.psd.layers.layerresources/vibaresource classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
## VibAResource constructor

Initialise une nouvelle instance du[`VibAResource`](../../vibaresource) classe.

```csharp
public VibAResource()
```

### Exemples

L'exemple de code suivant illustre la prise en charge de la ressource VibAResource.

```csharp
[C#]

// Exemple de prise en charge de la lecture et de l'écriture de Vibration Resource lors de l'exécution.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Voir également

* class [VibAResource](../../vibaresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
