---
title: XzArchiveSettings
second_title: Aspose.ZIP for .NET API Referansı
description: Yeni bir örneğini başlatırXzArchiveSettingsaspose.zip.xz.settings/xzarchivesettings tek LZMA2 sıkıştırması kullanan sınıf.
type: docs
weight: 10
url: /tr/net/aspose.zip.xz.settings/xzarchivesettings/xzarchivesettings/
---
## XzArchiveSettings() {#constructor}

Yeni bir örneğini başlatır[`XzArchiveSettings`](../../xzarchivesettings) tek LZMA2 sıkıştırması kullanan sınıf.

```csharp
public XzArchiveSettings()
```

### Notlar

LZMA2 filtre boyutundaki varsayılan sözlük 16 megabayta eşittir, varsayılan blok boyutu 64 megabayta eşittir, varsayılan sağlama toplamı türü CRC32'dir.

### Ayrıca bakınız

* class [XzArchiveSettings](../../xzarchivesettings)
* ad alanı [Aspose.Zip.Xz.Settings](../../xzarchivesettings)
* toplantı [Aspose.Zip](../../../)

---

## XzArchiveSettings(XzFilterSettings[], long, XzCheckType) {#constructor_1}

Yeni bir örneğini başlatır[`XzArchiveSettings`](../../xzarchivesettings) özel parametrelere sahip sınıf.

```csharp
public XzArchiveSettings(XzFilterSettings[] filters, long blockSize, XzCheckType checkType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filters | XzFilterSettings[] | Filtreler (kompresörler) oluşturmak için sıralı olarak uygulanacak[`XzArchive`](../../../aspose.zip.xz/xzarchive) . Ya tek olabilir[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings) veya bir çift[`XzBcjX86FilterSettings`](../../xzbcjx86filtersettings) ve[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings) |
| blockSize | Int64 | Boyut xz arşiv bloğu. |
| checkType | XzCheckType | Sıkıştırılmamış veriler için sağlama toplamı hesaplama türü. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *blockSize* negatif. |
| ArgumentNullException | *filters* boş |
| ArgumentException | *filters* birden az veya ikiden fazla filtreye sahip veya son filtre yok[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings). |

### Örnekler

```csharp
using (FileStream xzFile = File.Open("archive.xz", FileMode.Create))
{
    XzLZMA2FilterSettings filter = new XzLZMA2FilterSettings(5242880);
    XzArchiveSettings settings = new XzArchiveSettings(new XzFilterSettings[] {filter}, 10485760, XzCheckType.Crc32);
    using (var archive = new XzArchive(settings))
    {
        archive.SetSource("data.bin");
        archive.Save(xzFile);
     }
}
```

### Ayrıca bakınız

* class [XzFilterSettings](../../xzfiltersettings)
* enum [XzCheckType](../../xzchecktype)
* class [XzArchiveSettings](../../xzarchivesettings)
* ad alanı [Aspose.Zip.Xz.Settings](../../xzarchivesettings)
* toplantı [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
