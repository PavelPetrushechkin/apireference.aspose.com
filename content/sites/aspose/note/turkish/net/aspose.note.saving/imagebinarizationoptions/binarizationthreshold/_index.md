---
title: BinarizationThreshold
second_title: Aspose.Note for .NET API Referansı
description: Sabit eşik ikilileştirme yöntemi için eşik değerini alır veya ayarlar. Varsayılan değer 128dir.
type: docs
weight: 30
url: /tr/net/aspose.note.saving/imagebinarizationoptions/binarizationthreshold/
---
## ImageBinarizationOptions.BinarizationThreshold property

Sabit eşik ikilileştirme yöntemi için eşik değerini alır veya ayarlar. Varsayılan değer 128'dir.

```csharp
public byte BinarizationThreshold { get; set; }
```

### Örnekler

Sabit eşik kullanılarak bir belgenin ikili görüntü olarak nasıl kaydedileceğini gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Belgeyi Aspose.Note'a yükleyin.
Document oneFile = new Document(dataDir + "Aspose.one");

dataDir = dataDir + "SaveToBinaryImageUsingFixedThreshold_out.png";

// Belgeyi gif olarak kaydedin.
oneFile.Save(dataDir, new ImageSaveOptions(SaveFormat.Png)
                          {
                              ColorMode = ColorMode.BlackAndWhite,
                              BinarizationOptions = new ImageBinarizationOptions()
                                                        {
                                                            BinarizationMethod = BinarizationMethod.FixedThreshold,
                                                            BinarizationThreshold = 123
                                                        }
                          });
```

### Ayrıca bakınız

* class [ImageBinarizationOptions](../../imagebinarizationoptions)
* ad alanı [Aspose.Note.Saving](../../imagebinarizationoptions)
* toplantı [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
