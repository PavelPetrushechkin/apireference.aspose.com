---
title: BackgroundColor
second_title: Aspose.Note for .NET API Referansı
description: Sayfanın arka plan rengini alır veya ayarlar.
type: docs
weight: 30
url: /tr/net/aspose.note/page/backgroundcolor/
---
## Page.BackgroundColor property

Sayfanın arka plan rengini alır veya ayarlar.

```csharp
public Color BackgroundColor { get; set; }
```

### Örnekler

Sayfanın arka plan renginin nasıl ayarlanacağını gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_Pages();

// OneNote belgesini yükle ve ilk çocuğu al           
Document document = new Document(Path.Combine(dataDir, "Aspose.one"));

foreach (var page in document)
{
    page.BackgroundColor = Color.BlueViolet;
}

document.Save(Path.Combine(dataDir, "SetPageBackgroundColor.one"));
```

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [Aspose.Note](../../page)
* toplantı [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
