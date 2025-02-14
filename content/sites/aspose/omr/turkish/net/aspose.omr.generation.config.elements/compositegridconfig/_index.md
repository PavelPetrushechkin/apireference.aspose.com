---
title: CompositeGridConfig
second_title: Aspose.OMR for .NET API Referansı
description: Izgara öğesi. Bir dizi baloncuk üretin. Doldurulan her balon bileşik değerde bir sembolü temsil eder Tüm işaretli semboller tek bir değerde birleştirilir
type: docs
weight: 110
url: /tr/net/aspose.omr.generation.config.elements/compositegridconfig/
---
## CompositeGridConfig class

Izgara öğesi. Bir dizi baloncuk üretin. Doldurulan her balon, bileşik değerde bir sembolü temsil eder Tüm işaretli semboller tek bir değerde birleştirilir

```csharp
public class CompositeGridConfig : BaseConfig
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CompositeGridConfig](compositegridconfig)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BubbleType](../../aspose.omr.generation.config.elements/compositegridconfig/bubbletype) { get; set; } | Bir balonun türü |
| [Column](../../aspose.omr.generation.config.elements/compositegridconfig/column) { get; set; } | Öğe çok sütunlu üst öğede çizildiğinde - konumu temsil eder. |
| [ColumnsCount](../../aspose.omr.generation.config.elements/compositegridconfig/columnscount) { get; set; } | Izgara içindeki sütun miktarı. Her sütun, value sonucundaki tek sembolü temsil eder_ Tutar şuna eşit olmalıdır[`ExtraRow`](./extrarow) sütun miktarı |
| [ExtraRow](../../aspose.omr.generation.config.elements/compositegridconfig/extrarow) { get; set; } | Varsayılan değerlerin üzerine yerleştirilecek sütuna özgü değerler -[`Values`](./values). İki boyutlu dizi olarak sunulur. İlk - satır. İkinci - column. Her dize balonun içindeki metni temsil eder. dize boşsa balon yerleştirilmez. Sütun sayısı şuna eşit olmalıdır[`ColumnsCount`](./columnscount) |
| [GridAlignment](../../aspose.omr.generation.config.elements/compositegridconfig/gridalignment) { get; set; } | Izgara hizalaması, sayfa 'de ızgaranın nereye çizilmesi gerektiğini gösterir |
| [GridOrientation](../../aspose.omr.generation.config.elements/compositegridconfig/gridorientation) { get; set; } | Izgara yönü: yatay veya dikey. Alt öğelerin nasıl konumlandırılması gerektiğini gösterir |
| [HeaderBorderColor](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordercolor) { get; set; } | Kare kenarlık color |
| [HeaderBorderSize](../../aspose.omr.generation.config.elements/compositegridconfig/headerbordersize) { get; set; } | Kare kenarlık size |
| [HeaderType](../../aspose.omr.generation.config.elements/compositegridconfig/headertype) { get; set; } | Grid başlangıcında ne tür bir öğenin çizileceğini belirtir |
| override [Name](../../aspose.omr.generation.config.elements/compositegridconfig/name) { get; set; } | Izgara adı. tanıma içinde tanımlayıcı olarak kullanıldı |
| [RotationAngle](../../aspose.omr.generation.config.elements/compositegridconfig/rotationangle) { get; set; } | Izgara öğesinin kendi ekseni etrafında dönüşünü açıklayın. "90" - CompositeGrid'i 90 derece döndürün "-90" - ComopositeGrid'i -90 dereceye döndürün |
| override [Type](../../aspose.omr.generation.config.elements/compositegridconfig/type) { get; set; } | Omr öğesinin türü. JSON serileştirme için gerekli alan. |
| [Values](../../aspose.omr.generation.config.elements/compositegridconfig/values) { get; set; } | Her sütundaki olası sembolleri tanımlayacak dizeler topluluğu. Sütuna özgü değerler[`ExtraRow`](./extrarow) |
| [XPosition](../../aspose.omr.generation.config.elements/compositegridconfig/xposition) { get; set; } | Sayfadaki Izgara X konumu, hizalamayı geçersiz kılar |
| [YPosition](../../aspose.omr.generation.config.elements/compositegridconfig/yposition) { get; set; } | Sayfadaki Izgara Y konumu, hizalamayı geçersiz kılar |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [BubbleSize](../../aspose.omr.generation.config.elements/compositegridconfig/bubblesize) | Bir balonun boyutu |
| [VerticalMargin](../../aspose.omr.generation.config.elements/compositegridconfig/verticalmargin) | Lines arasındaki boşluk |

### Ayrıca bakınız

* class [BaseConfig](../../aspose.omr.generation.config/baseconfig)
* ad alanı [Aspose.OMR.Generation.Config.Elements](../../aspose.omr.generation.config.elements)
* toplantı [Aspose.OMR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OMR.dll -->
