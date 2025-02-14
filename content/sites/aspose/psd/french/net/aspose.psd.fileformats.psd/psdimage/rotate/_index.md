---
title: Rotate
second_title: Référence de l'API Aspose.PSD pour .NET
description: Faire pivoter limage autour du centre.
type: docs
weight: 610
url: /fr/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Faire pivoter l'image autour du centre.

```csharp
public override void Rotate(float angle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| angle | Single | L'angle de rotation en degrés. Les valeurs positives tourneront dans le sens des aiguilles d'une montre. |

### Exemples

Le code suivant montre la possibilité de faire pivoter l'image selon une valeur d'angle spécifique.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotation de l'image entière
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Couche tournante
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Voir également

* class [PsdImage](../../psdimage)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage)
* Assemblée [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Faire pivoter l'image autour du centre.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| angle | Single | L'angle de rotation en degrés. Les valeurs positives tourneront dans le sens des aiguilles d'une montre. |
| resizeProportionally | Boolean | si réglé sur`vrai` la taille de votre image sera modifiée en fonction des projections du rectangle pivoté (points d'angle) dans un autre cas qui laisse les dimensions intactes et seul le contenu de l'image interne est pivoté. |
| backgroundColor | Color | Couleur du fond. |

### Voir également

* struct [Color](../../../aspose.psd/color)
* class [PsdImage](../../psdimage)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
