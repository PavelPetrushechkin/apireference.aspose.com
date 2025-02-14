---
title: Bytes
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient le magasin de données dimage.
type: docs
weight: 50
url: /fr/net/aspose.note/image/bytes/
---
## Image.Bytes property

Obtient le magasin de données d'image.

```csharp
public byte[] Bytes { get; }
```

### Exemples

Montre comment obtenir une image à partir d'un document.

```csharp
// Le chemin d'accès au répertoire des documents.
string dataDir = RunExamples.GetDataDir_Images();

// Charge le document dans Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Récupère tous les nœuds Image
IList<Aspose.Note.Image> nodes = oneFile.GetChildNodes<Aspose.Note.Image>();

foreach (Aspose.Note.Image image in nodes)
{
    using (MemoryStream stream = new MemoryStream(image.Bytes))
    {
        using (Bitmap bitMap = new Bitmap(stream))
        {
            // Enregistre les octets de l'image dans un fichier
            bitMap.Save(String.Format(dataDir + "{0}", Path.GetFileName(image.FileName)));
        }
    }
}
```

### Voir également

* class [Image](../../image)
* espace de noms [Aspose.Note](../../image)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
