---
title: SetLicense
second_title: Aspose.GIS for .NET API Referansı
description: Bileşeni lisanslar.
type: docs
weight: 20
url: /tr/net/aspose.gis/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

### Notlar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen montajını içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesinde yerleşik bir kaynak.

**Not:**.NET Compact Framework üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:

1. Açık yol.

2. İstemcinin çağıran derlemesinde yerleşik bir kaynak.

### Örnekler

Bu örnekte, bileşenini içeren klasörde MyLicense.lic adlı bir lisans dosyası, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynakları. Tam veya kısa dosya adı veya gömülü bir kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### Ayrıca bakınız

* class [License](../../license)
* ad alanı [Aspose.Gis](../../license)
* toplantı [Aspose.GIS](../../../)

---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Lisansı içeren bir akış. |

### Notlar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.

### Örnekler

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Ayrıca bakınız

* class [License](../../license)
* ad alanı [Aspose.Gis](../../license)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
