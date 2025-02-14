---
title: Style
second_title: Référence de l'API Aspose.PSD pour .NET
description: Obtient le style de police analysé à partir du nom de la sousfamille
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Obtient le style de police analysé à partir du nom de la sous-famille

```csharp
public FontStyle Style { get; }
```

### Valeur de la propriété

Style de police analysé à partir du nom de la sous-famille

### Exemples

Le code suivant montre comment Aspose.PSD obtient les propriétés de mise en forme en ligne du calque de texte.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Charger une image existante dans une instance de la classe PsdImage
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // obtient les polices contenues dans le calque de texte
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### Voir également

* enum [FontStyle](../../../aspose.psd/fontstyle)
* class [TextFontInfo](../../textfontinfo)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
