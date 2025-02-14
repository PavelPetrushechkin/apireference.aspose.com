---
title: Metered
second_title: Aspose.OMR for .NET API Referansı
description: Ölçülen anahtarı ayarlamak için yöntemler sağlar.
type: docs
weight: 640
url: /tr/net/aspose.omr/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Metered](metered)() | Default_Constructor |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetMeteredKey](../../aspose.omr/metered/setmeteredkey)(string, string) | Ölçülen genel ve özel anahtarı ayarlar |
| static [GetConsumptionCredit](../../aspose.omr/metered/getconsumptioncredit)() | Tüketim kredisi alır |
| static [GetConsumptionQuantity](../../aspose.omr/metered/getconsumptionquantity)() | size tüketim dosyası alır |

### Örnekler

Bu örnekte, ölçülen genel ve özel anahtarın ayarlanması denenecektir

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ayrıca bakınız

* ad alanı [Aspose.OMR](../../aspose.omr)
* toplantı [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->
