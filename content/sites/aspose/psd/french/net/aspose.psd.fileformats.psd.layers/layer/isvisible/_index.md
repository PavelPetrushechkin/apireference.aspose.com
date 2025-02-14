---
title: IsVisible
second_title: Référence de l'API Aspose.PSD pour .NET
description: Obtient ou définit une valeur indiquant si le calque est visible
type: docs
weight: 170
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Obtient ou définit une valeur indiquant si le calque est visible

```csharp
public bool IsVisible { get; set; }
```

### Valeur de la propriété

`vrai` si cette instance est visible ; Par ailleurs,`faux` .

### Exemples

L'exemple suivant montre comment vous pouvez modifier la visibilité de LayerGroup dans Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportez des modifications aux noms de couches et enregistrez-les
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Désactive tout à l'intérieur d'un groupe
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Voir également

* class [Layer](../../layer)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
