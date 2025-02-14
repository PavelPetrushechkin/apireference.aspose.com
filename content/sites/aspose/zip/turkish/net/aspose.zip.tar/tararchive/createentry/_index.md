---
title: CreateEntry
second_title: Aspose.ZIP for .NET API Referansı
description: Arşiv içinde tek bir giriş oluşturun.
type: docs
weight: 80
url: /tr/net/aspose.zip.tar/tararchive/createentry/
---
## CreateEntry(string, Stream, FileSystemInfo) {#createentry_1}

Arşiv içinde tek bir giriş oluşturun.

```csharp
public TarEntry CreateEntry(string name, Stream source, FileSystemInfo fileInfo = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Girişin adı. |
| source | Stream | Giriş için giriş akışı. |
| fileInfo | FileSystemInfo | Sıkıştırılacak dosya veya klasörün meta verileri. |

### Geri dönüş değeri

Tar girişi örneği.

### istisnalar

| istisna | şart |
| --- | --- |
| PathTooLongException | *name* IEEE 1003.1-1998 standardına göre tar için çok uzun. |
| ArgumentException | Dosya adı, bir parçası olarak*name*, 100 sembolü aşıyor. |

### Notlar

Giriş adı yalnızca*name* parametre. İçinde sağlanan dosya adı*fileInfo* parametre giriş adını etkilemez.

*fileInfo* başvurabilirDirectoryInfo giriş dizin ise.

### Örnekler

```csharp
using (var archive = new TarArchive())
{
   archive.CreateEntry("bytes", new MemoryStream(new byte[] {0x00, 0xFF}));
   archive.Save(tarFile);
}
```

### Ayrıca bakınız

* class [TarEntry](../../tarentry)
* class [TarArchive](../../tararchive)
* ad alanı [Aspose.Zip.Tar](../../tararchive)
* toplantı [Aspose.Zip](../../../)

---

## CreateEntry(string, FileInfo, bool) {#createentry}

Arşiv içinde tek bir giriş oluşturun.

```csharp
public TarEntry CreateEntry(string name, FileInfo fileInfo, bool openImmediately = false)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Girişin adı. |
| fileInfo | FileInfo | Sıkıştırılacak dosya veya klasörün meta verileri. |
| openImmediately | Boolean | Dosyayı hemen açarsanız doğru, aksi takdirde dosyayı arşiv kaydında açın. |

### Geri dönüş değeri

Tar girişi örneği.

### istisnalar

| istisna | şart |
| --- | --- |
| PathTooLongException | *name* IEEE 1003.1-1998 standardına göre tar için çok uzun. |
| ArgumentException | Dosya adı, bir parçası olarak*name*, 100 sembolü aşıyor. |

### Notlar

Giriş adı yalnızca*name* parametre. İçinde sağlanan dosya adı*fileInfo* parametre giriş adını etkilemez.

*fileInfo* başvurabilirDirectoryInfo giriş dizin ise.

Dosya ile hemen açılırsa*openImmediately* parametre, arşiv atılana kadar bloke olur.

### Örnekler

```csharp
FileInfo fi = new FileInfo("data.bin");
using (var archive = new TarArchive())
{
   archive.CreateEntry("data.bin", fi);
   archive.Save(tarFile);
}
```

### Ayrıca bakınız

* class [TarEntry](../../tarentry)
* class [TarArchive](../../tararchive)
* ad alanı [Aspose.Zip.Tar](../../tararchive)
* toplantı [Aspose.Zip](../../../)

---

## CreateEntry(string, string, bool) {#createentry_2}

Arşiv içinde tek bir giriş oluşturun.

```csharp
public TarEntry CreateEntry(string name, string path, bool openImmediately = false)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| name | String | Girişin adı. |
| path | String | Sıkıştırılacak dosyanın yolu. |
| openImmediately | Boolean | Dosyayı hemen açarsanız doğru, aksi takdirde dosyayı arşiv kaydında açın. |

### Geri dönüş değeri

Tar girişi örneği.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *path* boş. |
| SecurityException | Arayan, erişim için gerekli izne sahip değil |
| ArgumentException | bu*path* boş, yalnızca boşluk içeriyor veya geçersiz karakterler içeriyor. - veya - Dosya adı, bir parçası olarak*name*, 100 sembolü aşıyor. |
| UnauthorizedAccessException | Dosyaya erişim*path* engellendi. |
| PathTooLongException | Belirtilmiş*path* , dosya adı veya her ikisi de sistem tarafından tanımlanan maksimum uzunluğu aşıyor. Örneğin, Windows tabanlı platformlarda yollar 248 karakterden ve dosya adları 260 karakterden az olmalıdır. - veya -*name* IEEE 1003.1-1998 standardına göre tar için çok uzun. |
| NotSupportedException | Dosya*path* dizenin ortasında iki nokta üst üste (:) içerir. |

### Notlar

Giriş adı yalnızca*name* parametre. İçinde sağlanan dosya adı*path* parametre giriş adını etkilemez.

Dosya ile hemen açılırsa*openImmediately* parametre, arşiv atılana kadar bloke olur.

### Örnekler

```csharp
using (var archive = new TarArchive())
{
    archive.CreateEntry("first.bin", "data.bin");
    archive.Save(outputTarFile);
}
```

### Ayrıca bakınız

* class [TarEntry](../../tarentry)
* class [TarArchive](../../tararchive)
* ad alanı [Aspose.Zip.Tar](../../tararchive)
* toplantı [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
