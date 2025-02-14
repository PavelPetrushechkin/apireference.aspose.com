---
title: IsBold
second_title: Référence de l'API Aspose.Note pour .NET
description: Obtient ou définit une valeur indiquant si le style de texte est en gras.
type: docs
weight: 60
url: /fr/net/aspose.note/style/isbold/
---
## Style.IsBold property

Obtient ou définit une valeur indiquant si le style de texte est en gras.

```csharp
public bool IsBold { get; set; }
```

### Exemples

Mettons l'accent sur les titres de page parmi les autres en-têtes en augmentant la taille de la police.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Charge le document dans Aspose.Note.
Document document = new Document(dataDir + "Aspose.one");

// Parcourt les titres de la page.
foreach (var title in document.Select(e => e.Title.TitleText))
{
    title.ParagraphStyle.FontSize = 24;
    title.ParagraphStyle.IsBold = true;

    foreach (var run in title.TextRuns)
    {
        run.Style.FontSize = 24;
        run.Style.IsBold = true;
    }
}

document.Save(Path.Combine(dataDir, "ChangePageTitleStyle.pdf"));
```

Soulignons les dernières modifications du texte en les mettant en surbrillance.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Charge le document dans Aspose.Note.
Document document = new Document(dataDir + "Aspose.one");

// Récupère les nœuds RichText modifiés la semaine dernière.
var richTextNodes = document.GetChildNodes<RichText>().Where(e => e.LastModifiedTime >= DateTime.Today.Subtract(TimeSpan.FromDays(7)));

foreach (var node in richTextNodes)
{
    // Définir la couleur de surbrillance
    node.ParagraphStyle.Highlight = Color.DarkGreen;
    foreach (var run in node.TextRuns)
    {
        // Définir la couleur de surbrillance
        run.Style.Highlight = Color.DarkSeaGreen;
    }
}

document.Save(Path.Combine(dataDir, "HighlightAllRecentChanges.pdf"));
```

### Voir également

* class [Style](../../style)
* espace de noms [Aspose.Note](../../style)
* Assemblée [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
