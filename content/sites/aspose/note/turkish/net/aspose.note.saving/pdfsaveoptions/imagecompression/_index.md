---
title: ImageCompression
second_title: Aspose.Note for .NET API Referansı
description: PDF dosyasındaki görüntülere uygulanan sıkıştırma türünü alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.note.saving/pdfsaveoptions/imagecompression/
---
## PdfSaveOptions.ImageCompression property

PDF dosyasındaki görüntülere uygulanan sıkıştırma türünü alır veya ayarlar.

```csharp
public PdfImageCompression ImageCompression { get; set; }
```

### Örnekler

Belirli ayarlar kullanılarak bir belgenin pdf formatında nasıl kaydedileceğini gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Belgeyi Aspose.Note'a yükleyin.
Document doc = new Document(dataDir + "Aspose.one");

// PdfSaveOptions nesnesini başlat
PdfSaveOptions opts = new PdfSaveOptions
                          {
                              // Jpeg sıkıştırmasını kullan
                              ImageCompression = Saving.Pdf.PdfImageCompression.Jpeg,

                              // JPEG sıkıştırması için kalite
                              JpegQuality = 90
                          };

dataDir = dataDir + "Document.SaveWithOptions_out.pdf";
doc.Save(dataDir, opts);
```

### Ayrıca bakınız

* enum [PdfImageCompression](../../../aspose.note.saving.pdf/pdfimagecompression)
* class [PdfSaveOptions](../../pdfsaveoptions)
* ad alanı [Aspose.Note.Saving](../../pdfsaveoptions)
* toplantı [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
