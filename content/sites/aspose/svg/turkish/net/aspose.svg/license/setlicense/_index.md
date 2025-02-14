---
title: SetLicense
second_title: Aspose.SVG for .NET API Referansı
description: Bileşeni lisanslar.
type: docs
weight: 20
url: /tr/net/aspose.svg/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| licenseName | String | Tam veya kısa dosya adı olabilir veya gömülü bir kaynağın adı. Değerlendirme moduna geçmek için boş bir dize kullanın. |

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

2. Aspose bileşeni JAR dosyasını içeren klasör.

3. İstemcinin çağıran JAR dosyasını içeren klasör.

### Örnekler

Bu örnekte, içeren klasörde MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. bileşen, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

bileşen jar dosyası:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ayrıca bakınız

* class [License](../../license)
* ad alanı [Aspose.Svg](../../license)
* toplantı [Aspose.SVG](../../../)

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
```

### Ayrıca bakınız

* class [License](../../license)
* ad alanı [Aspose.Svg](../../license)
* toplantı [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
