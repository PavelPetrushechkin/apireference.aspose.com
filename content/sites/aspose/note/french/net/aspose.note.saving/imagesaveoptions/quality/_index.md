---
title: Quality
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient ou définit une valeur déterminant la qualité de limage enregistrée. Cette valeur est transmise au codec en tant que paramètre System.Drawing.Imaging.Encoder.Quality.
type: docs
weight: 40
url: /fr/net/aspose.note.saving/imagesaveoptions/quality/
---
## ImageSaveOptions.Quality property

Obtient ou définit une valeur déterminant la qualité de l'image enregistrée. Cette valeur est transmise au codec en tant que paramètre System.Drawing.Imaging.Encoder.Quality.

```csharp
public int Quality { get; set; }
```

### Remarques

La plage de valeurs utiles pour la catégorie de qualité est de 0 à 100. Plus le nombre spécifié est faible, plus la compression est élevée et donc plus la qualité de l'image est faible. Zéro vous donnerait la qualité d'image la plus faible et 100 la plus élevée . La valeur par défaut est 90.

### Exemples

Montre comment définir une qualité d'image lors de l'enregistrement d'un document en tant qu'image au format JPEG.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Charge le document dans Aspose.Note.
Document doc = new Document(dataDir + "Aspose.one");

dataDir = dataDir + "SetOutputImageResolution_out.jpg";

// Enregistre le document.
doc.Save(dataDir, new ImageSaveOptions(SaveFormat.Jpeg) { Quality = 100 });
```

Montre comment enregistrer un document en tant qu'image au format Tiff à l'aide de la compression Jpeg.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Charge le document dans Aspose.Note.
Document oneFile = new Document(Path.Combine(dataDir, "Aspose.one"));

var dst = Path.Combine(dataDir, "SaveToTiffUsingJpegCompression.tiff");

// Enregistre le document.
oneFile.Save(dst, new ImageSaveOptions(SaveFormat.Tiff)
                      {
                          TiffCompression = TiffCompression.Jpeg,
                          Quality = 93
                      });
```

### Voir également

* class [ImageSaveOptions](../../imagesaveoptions)
* espace de noms [Aspose.Note.Saving](../../imagesaveoptions)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
