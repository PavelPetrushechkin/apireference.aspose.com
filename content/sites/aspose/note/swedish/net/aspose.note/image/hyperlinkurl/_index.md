---
title: HyperlinkUrl
second_title: Aspose.Note för .NET API-referens
description: Hämtar eller ställer in hyperlänken som är kopplad till bilden.
type: docs
weight: 110
url: /sv/net/aspose.note/image/hyperlinkurl/
---
## Image.HyperlinkUrl property

Hämtar eller ställer in hyperlänken som är kopplad till bilden.

```csharp
public string HyperlinkUrl { get; set; }
```

### Exempel

Visar hur man binder en hyperlänk till en bild.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Images(); 

var document = new Document();

var page = new Page(document);

var image = new Image(document, dataDir + "image.jpg") { HyperlinkUrl = "http://image.com" };

page.AppendChildLast(image);

document.AppendChildLast(page);

document.Save(dataDir + "Image with Hyperlink_out.one");
```

### Se även

* class [Image](../../image)
* namnutrymme [Aspose.Note](../../image)
* hopsättning [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
