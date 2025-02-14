---
title: Tags
second_title: Aspose.Note for .NET API Referansı
description: Bir paragrafın tüm etiketlerinin listesini alır.
type: docs
weight: 160
url: /tr/net/aspose.note/image/tags/
---
## Image.Tags property

Bir paragrafın tüm etiketlerinin listesini alır.

```csharp
public List<ITag> Tags { get; }
```

### Örnekler

Etiketli yeni resmin nasıl ekleneceğini gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_Tags();

// Document sınıfının bir nesnesini oluşturun
Document doc = new Document();

// Sayfa sınıfı nesnesini başlat
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// Outline sınıf nesnesini başlat
Outline outline = new Outline(doc);

// OutlineElement sınıf nesnesini başlat
OutlineElement outlineElem = new OutlineElement(doc);

// Bir resim yükle
Aspose.Note.Image image = new Aspose.Note.Image(doc, dataDir + "icon.jpg");

// Belge düğümüne resim ekle
outlineElem.AppendChildLast(image);
image.Tags.Add(NoteTag.CreateYellowStar());

// Anahat öğesi düğümü ekle
outline.AppendChildLast(outlineElem);

// Anahat düğümü ekle
page.AppendChildLast(outline);

// Sayfa düğümü ekle
doc.AppendChildLast(page);

// OneNote belgesini kaydet
dataDir = dataDir + "AddImageNodeWithTag_out.one";
doc.Save(dataDir);
```

### Ayrıca bakınız

* interface [ITag](../../itag)
* class [Image](../../image)
* ad alanı [Aspose.Note](../../image)
* toplantı [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
