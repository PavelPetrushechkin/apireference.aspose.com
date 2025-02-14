---
title: PsSaveOptions
second_title: Aspose.Page for .NET API Referansı
description: Bu sınıf belgeyi PostScript PS veya Encapsulated PostScript EPS dosyasına dönüştürme sürecini yönetmek için gerekli seçenekleri içerir.
type: docs
weight: 80
url: /tr/net/aspose.page.eps.device/pssaveoptions/
---
## PsSaveOptions class

Bu sınıf, belgeyi PostScript (PS) veya Encapsulated PostScript (EPS) dosyasına dönüştürme sürecini yönetmek için gerekli seçenekleri içerir.

```csharp
public class PsSaveOptions : SaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PsSaveOptions](pssaveoptions#constructor)() | Yeni bir örneğini başlatır[`PsSaveOptions`](../pssaveoptions) bayraklar için varsayılan değerler olan sınıf!:SuppressErrors (doğru) ve!:Debug (yanlış). |
| [PsSaveOptions](pssaveoptions#constructor_1)(bool) | Yeni bir örneğini başlatır[`PsSaveOptions`](../pssaveoptions) bayrak için varsayılan değerlere sahip sınıf!:Debug (yanlış). |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AdditionalFontsFolders](../../aspose.page/saveoptions/additionalfontsfolders) { get; set; } | Dönüştürücünün girdi belgesi için yazı tiplerini bulması gereken ek klasörleri belirtir. Varsayılan klasör, işletim sisteminin dahili ihtiyaçlar için yazı tiplerini bulduğu standart yazı tipleri klasörüdür. |
| virtual [Debug](../../aspose.page/saveoptions/debug) { get; set; } | Hata ayıklama bilgilerinin standart çıktı akışına yazdırılıp yazdırılmayacağını belirtir. |
| virtual [Exceptions](../../aspose.page/saveoptions/exceptions) { get; } | Bastırılmış dönüştürme hatalarının bir listesini döndürür!:SuppressErrors doğrudur. |
| [JpegQualityLevel](../../aspose.page/saveoptions/jpegqualitylevel) { get; set; } | Kalite kategorisi, bir görüntünün sıkıştırma düzeyini belirtir. Kullanılabilir değerler 0 ila 100'dür. Belirtilen sayı ne kadar düşükse, sıkıştırma o kadar yüksek ve dolayısıyla görüntünün kalitesi o kadar düşük olur. 0 değeri en düşük kaliteli görüntüyle sonuçlanırken, 100 sonuç en yüksek görüntü kalitesiyle sonuçlanır. |
| virtual [SupressErrors](../../aspose.page/saveoptions/supresserrors) { get; set; } | Hataların bastırılması gerekip gerekmediğini belirtir. [`Exceptions`](../../aspose.page/saveoptions/exceptions) list. false ise, ilk hata programı sonlandıracaktır. |

### Ayrıca bakınız

* class [SaveOptions](../../aspose.page/saveoptions)
* ad alanı [Aspose.Page.EPS.Device](../../aspose.page.eps.device)
* toplantı [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
