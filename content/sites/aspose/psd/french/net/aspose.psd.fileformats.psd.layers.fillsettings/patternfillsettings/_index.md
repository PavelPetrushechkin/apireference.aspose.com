---
title: PatternFillSettings
second_title: Référence de l'API Aspose.PSD pour .NET
description: Paramètres deffet de remplissage de motif
type: docs
weight: 2020
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---
## PatternFillSettings class

Paramètres d'effet de remplissage de motif

```csharp
public class PatternFillSettings : BaseFillSettings, IPatternFillSettings
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/alignwithlayer) { get; set; } | Obtient ou définit une valeur indiquant si [lien avec le calque]. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/color) { get; set; } | Obtient ou définit la couleur. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/filltype) { get; } | Le type de remplissage |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/horizontaloffset) { get; set; } | Obtient ou définit le décalage horizontal. |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/linked) { get; set; } | Obtient ou définit une valeur indiquant si cette[`PatternFillSettings`](../patternfillsettings) est lié. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patterndata) { get; set; } | Obtient ou définit les données de modèle. |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternheight) { get; set; } | Obtient ou définit la hauteur du motif. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternid) { get; set; } | Obtient ou définit l'identifiant du modèle. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternname) { get; set; } | Obtient ou définit le nom du modèle. |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternwidth) { get; set; } | Obtient ou définit la largeur du motif. |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/pointtype) { get; set; } | Obtient ou définit le type du point. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/scale) { get; set; } | Obtient ou définit l'échelle. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/verticaloffset) { get; set; } | Obtient ou définit le décalage vertical. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/generatelfx2resourcenodes)(string, Color, string, string, double, bool, PointF) | Génère les nœuds de ressources LFX2. |

### Exemples

Le code suivant illustre la prise en charge de la modification du motif de calque de remplissage.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PatternFillLayer_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            FillLayer fillLayer = (FillLayer)layer;
            PatternFillSettings fillSettings = (PatternFillSettings)fillLayer.FillSettings;

            if (fillSettings.HorizontalOffset != -46 ||
                fillSettings.VerticalOffset != -45 ||
                fillSettings.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5".ToUpperInvariant() ||
                fillSettings.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares" ||
                fillSettings.AlignWithLayer != true ||
                fillSettings.Linked != true ||
                fillSettings.PatternHeight != 64 ||
                fillSettings.PatternWidth != 64 ||
                fillSettings.PatternData.Length != 4096 ||
                Math.Abs(fillSettings.Scale - 50) > tolerance)
            {
                throw new Exception("PSD Image was read wrong");
            }

            // Édition 
            fillSettings.Scale = 300;
            fillSettings.HorizontalOffset = 2;
            fillSettings.VerticalOffset = -20;
            fillSettings.PatternData = new int[]
            {
                Color.Red.ToArgb(), Color.Blue.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Red.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Blue.ToArgb(),  Color.Red.ToArgb()
            };
            fillSettings.PatternHeight = 3;
            fillSettings.PatternWidth = 3;
            fillSettings.AlignWithLayer = false;
            fillSettings.Linked = false;
            fillSettings.PatternId = Guid.NewGuid().ToString();
            fillLayer.Update();
            break;
        }
    }
    im.Save(exportPath);
}
```

Le code suivant illustre la prise en charge du calque d'effet de trait avec le type de remplissage - Motif.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (expected is Array && actual is Array)
    {
        Array array1 = (Array)expected;
        Array array2 = (Array)actual;
        AssertAreEqual(array1.Length, array2.Length);

        for (int i = 0; i < array1.Length; i++)
        {
            AssertAreEqual(array1.GetValue(i), array2.GetValue(i));
        }
        return;
    }

    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokePatternChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

// Préparation de nouvelles données
var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 4);
var guid = Guid.NewGuid();

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternStroke.BlendMode);
    AssertAreEqual((byte)255, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

    patternStroke.Opacity = 127;
    patternStroke.BlendMode = BlendMode.Color;

    PattResource resource;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
            resource.Patterns[0].PatternId = guid.ToString();
            resource.Patterns[0].Name = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

            resource.Patterns[0].SetPattern(newPattern, newPatternBounds);
        }
    }

    ((PatternFillSettings)patternStroke.FillSettings).PatternName = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

    ((PatternFillSettings)patternStroke.FillSettings).PatternId = guid.ToString() + "\0";
    im.Save(exportPath);
}

// Tester le fichier après modification
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    PattResource resource = null;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
        }
    }

    if (resource == null)
    {
        throw new Exception("PattResource not found");
    }

    // Vérifier les données du motif
    AssertAreEqual(newPattern, resource.Patterns[0].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[0].Width, resource.Patterns[0].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[0].PatternId);

    AssertAreEqual(BlendMode.Color, patternStroke.BlendMode);
    AssertAreEqual((byte)127, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;

    AssertAreEqual(FillType.Pattern, fillSettings.FillType);
}
```

### Voir également

* class [BaseFillSettings](../basefillsettings)
* interface [IPatternFillSettings](../ipatternfillsettings)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
