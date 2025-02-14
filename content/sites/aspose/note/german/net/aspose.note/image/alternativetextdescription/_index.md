---
title: AlternativeTextDescription
second_title: Aspose.Note für .NET-API-Referenz
description: Holt oder setzt einen Body oder alternativen Text für das Bild.
type: docs
weight: 30
url: /de/net/aspose.note/image/alternativetextdescription/
---
## Image.AlternativeTextDescription property

Holt oder setzt einen Body oder alternativen Text für das Bild.

```csharp
public string AlternativeTextDescription { get; set; }
```

### Beispiele

Zeigt, wie eine Textbeschreibung für ein Bild festgelegt wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Images();

var document = new Document();
var page = new Page(document);
var image = new Image(document, dataDir + "image.jpg")
            {
                AlternativeTextTitle = "This is an image's title!",
                AlternativeTextDescription = "And this is an image's description!"
            };
page.AppendChildLast(image);
document.AppendChildLast(page);

dataDir = dataDir + "ImageAlternativeText_out.one";
document.Save(dataDir);
```

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Note](../../image)
* Montage [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
