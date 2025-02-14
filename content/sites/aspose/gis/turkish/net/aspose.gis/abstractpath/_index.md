---
title: AbstractPath
second_title: Aspose.GIS for .NET API Referansı
description: BirSoyutYol dosya sistemine benzer bir ortamda benzersiz bir konum belirten sınıflar için bir temel sınıftır diğerleri arasında yerel dosya sistemi uzak dosya deposu veya ZIP arşivi gibi.
type: docs
weight: 10
url: /tr/net/aspose.gis/abstractpath/
---
## AbstractPath class

Bir`SoyutYol` dosya sistemine benzer bir ortamda benzersiz bir konum belirten sınıflar için bir temel sınıftır, diğerleri arasında yerel dosya sistemi, uzak dosya deposu veya ZIP arşivi gibi.

```csharp
public abstract class AbstractPath
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| abstract [Location](../../aspose.gis/abstractpath/location) { get; } | Bunun konumunun bir dize temsilini alır`SoyutYol` . |
| abstract [Separator](../../aspose.gis/abstractpath/separator) { get; } | Dizin düzeylerini ayırmak için kullanılan bir ayırıcı karakter alır.[`Location`](./location) sicim. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromLocalPath](../../aspose.gis/abstractpath/fromlocalpath)(string) | Bir[`AbstractPath`](../abstractpath) yerel dosya sistemindeki bir konumu temsil eder. |
| static [FromStream](../../aspose.gis/abstractpath/fromstream)(Stream) | Bir[`AbstractPath`](../abstractpath) birStream . |
| virtual [Combine](../../aspose.gis/abstractpath/combine)(string) | Bunu birleştirir[`AbstractPath`](../abstractpath) belirtilen yol bileşenleriyle. |
| abstract [Delete](../../aspose.gis/abstractpath/delete)() | Bu yolla işaret edilen bir dosyayı siler. |
| [GetExtension](../../aspose.gis/abstractpath/getextension)() | Bunun uzantısını döndürür[`AbstractPath`](../abstractpath) . |
| [GetFileName](../../aspose.gis/abstractpath/getfilename)() | Bunun dosya adını ve uzantısını döndürür[`AbstractPath`](../abstractpath) . |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension)() | Bunun dosya adını döndürür[`AbstractPath`](../abstractpath) uzantı olmadan. |
| abstract [IsFile](../../aspose.gis/abstractpath/isfile)() | Bu yolun okuma için açılabilen mevcut bir dosyaya işaret edip etmediğini gösteren bir değer alır. |
| abstract [ListDirectory](../../aspose.gis/abstractpath/listdirectory)() | Bunun içinde bulunan yolları döndürür`SoyutYol` , eğer bir dizinse. |
| abstract [Open](../../aspose.gis/abstractpath/open)(FileAccess) | Bunu açar`SoyutYol`dosya olarak. |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension)(string) | Yeni bir[`AbstractPath`](../abstractpath) dosya uzantısı belirtilen değere değiştirildi. |

### Notlar

Bir`SoyutYol` yerel dosya sisteminde bir konum, uzak bir filesystem üzerinde bir konum veya Azure Blob depolama gibi bir harici depolama vb. belirtebilir. Konum, mevcut veya mevcut olmayan bir dosya benzeri nesnelere, dizin benzeri nesnelere işaret edebilir veya ait olduğu ortam için makul olan başka bir anlama sahip olabilir. Örnek olarak, bir`SoyutYol` yerel dosya sistemindeki bir konumu temsil eden mirasçı, var olan bir dosyasına, dizine veya dosya sisteminde henüz oluşturulmamış bir yere işaret edebilir. Dosya sistemi benzeri yeni bir depolamayı kullanıcılar için kullanılabilir hale getirmek için`Aspose.GIS` kişi bu class sınıfını devralmalı ve onun soyut yöntemlerini uygulamalıdır.

### Ayrıca bakınız

* ad alanı [Aspose.Gis](../../aspose.gis)
* toplantı [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
