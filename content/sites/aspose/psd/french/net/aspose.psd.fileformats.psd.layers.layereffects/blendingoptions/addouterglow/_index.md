---
title: AddOuterGlow
second_title: Référence de l'API Aspose.PSD pour .NET
description: Ajoute leffet de lueur externe.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Ajoute l'effet de lueur externe.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Return_Value

créé[`OuterGlowEffect`](../../outergloweffect) objet

### Exemples

Le code suivant illustre la prise en charge d'OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Voir également

* class [OuterGlowEffect](../../outergloweffect)
* class [BlendingOptions](../../blendingoptions)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
