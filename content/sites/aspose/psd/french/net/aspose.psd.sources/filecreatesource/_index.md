---
title: FileCreateSource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Représente une source de fichier pour la création.
type: docs
weight: 5520
url: /fr/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Représente une source de fichier pour la création.

```csharp
public sealed class FileCreateSource : FileSource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FileCreateSource](filecreatesource#constructor)(string) | Initialise une nouvelle instance du[`FileCreateSource`](../filecreatesource) classe. |
| [FileCreateSource](filecreatesource#constructor_1)(string, bool) | Initialise une nouvelle instance du[`FileCreateSource`](../filecreatesource) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath) { get; } | Obtient le chemin du fichier à créer. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal) { get; } | Obtient une valeur indiquant si le fichier sera temporel. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer)() | Obtient le conteneur de flux. |

### Exemples

Cet exemple illustre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface de l'image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et GraphicsPath

```csharp
[C#]

// Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface graphique
    graphics.Clear(Color.Wheat);

    // Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Créer une instance de SolidBrush ayant la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée les options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // Enregistrer toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir également

* class [FileSource](../filesource)
* espace de noms [Aspose.PSD.Sources](../../aspose.psd.sources)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
