---
title: License
second_title: Aspose.SVG for .NET API Referansı
description: Bileşeni lisanslamak için yöntemler sağlar.
type: docs
weight: 2160
url: /tr/net/aspose.svg/license/
---
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public class License
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [License](license)() | Bu sınıfın yeni bir örneğini başlatır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense)(Stream) | Bileşeni lisanslar. |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense_1)(string) | Bileşeni lisanslar. |

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

* ad alanı [Aspose.Svg](../../aspose.svg)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
