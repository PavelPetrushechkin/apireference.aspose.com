---
title: ExtractToDirectory
second_title: Aspose.ZIP for .NET API Referansı
description: Arşivdeki tüm dosyaları sağlanan dizine çıkarır.
type: docs
weight: 70
url: /tr/net/aspose.zip.sevenzip/sevenziparchive/extracttodirectory/
---
## SevenZipArchive.ExtractToDirectory method

Arşivdeki tüm dosyaları sağlanan dizine çıkarır.

```csharp
public void ExtractToDirectory(string destinationDirectory, string password = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| destinationDirectory | String | Ayıklanan dosyaların yerleştirileceği dizinin yolu. |
| password | String | Şifre çözme için isteğe bağlı şifre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *destinationDirectory* boş. |
| PathTooLongException | Belirtilen yol, dosya adı veya her ikisi de sistem tarafından tanımlanan maksimum uzunluğu aşıyor. Örneğin, Windows tabanlı platformlarda yollar 248 karakterden ve dosya adları 260 karakterden az olmalıdır. |
| SecurityException | Arayan, mevcut dizine erişmek için gerekli izne sahip değil. |
| NotSupportedException | Dizin yoksa, yol, sürücü etiketinin ("C:\") parçası olmayan iki nokta üst üste karakteri (:) içerir. |
| ArgumentException | *destinationDirectory* sıfır uzunlukta bir dizedir, yalnızca boşluk içerir veya bir veya daha fazla geçersiz karakter içerir. System.IO.Path.GetInvalidPathChars yöntemini kullanarak geçersiz karakterleri sorgulayabilirsiniz. -veya- yolun önüne yalnızca bir iki nokta üst üste karakteri (:) eklenir veya bu karakter içerir. |
| IOException | Yol tarafından belirtilen dizin bir dosyadır. -veya- Ağ adı bilinmiyor. |

### Notlar

Dizin yoksa, oluşturulacaktır.

### Örnekler

```csharp
using (var archive = new SevenZipArchive("archive.7z")) 
{ 
   archive.ExtractToDirectory("C:\extracted");
}
```

### Ayrıca bakınız

* class [SevenZipArchive](../../sevenziparchive)
* ad alanı [Aspose.Zip.SevenZip](../../sevenziparchive)
* toplantı [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
