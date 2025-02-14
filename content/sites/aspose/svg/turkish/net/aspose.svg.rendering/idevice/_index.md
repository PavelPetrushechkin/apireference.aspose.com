---
title: IDevice
second_title: Aspose.SVG for .NET API Referansı
description: Yollar metin ve resimler gibi grafik öğelerin özel olarak oluşturulmasını destekleyen yöntemleri ve özellikleri tanımlar.
type: docs
weight: 2770
url: /tr/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Yollar, metin ve resimler gibi grafik öğelerin özel olarak oluşturulmasını destekleyen yöntemleri ve özellikleri tanımlar.

```csharp
public interface IDevice : IDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext) { get; } | Grafik bağlamını alır. |
| [Options](../../aspose.svg.rendering/idevice/options) { get; } | Oluşturma seçeneklerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect)(RectangleF) | Geçerli yola tam bir alt yol olarak bir dikdörtgen ekler. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument)(Document) | Belgeyi oluşturmaya başlar. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement)(Element, RectangleF) | Öğeyi oluşturmaya başlar. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| [Clip](../../aspose.svg.rendering/idevice/clip)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak, geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem, geçerli yolu sonlandırır. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath)() | Geçerli noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Geçerli alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu operatör geçerli alt yolu sonlandırır. Geçerli yola başka bir segment eklenmesi yeni bir alt yolu başlatır, yeni segment "ClosePath" yöntemiyle ulaşılan uç noktada başlasa bile. |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, Bézier kontrol noktaları olarak pt1 ve pt2 kullanılarak mevcut noktadan pt3, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage)(byte[], ImageType, RectangleF) | Belirtilen resmi çizer. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument)() | Belgenin oluşturulmasını bitirir. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement)(Element) | Öğenin oluşturulmasını sona erdirir. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage)() | Geçerli sayfanın oluşturulmasını sona erdirir. |
| [Fill](../../aspose.svg.rendering/idevice/fill)(FillMode) | Geçerli yol tarafından çevrelenen tüm bölgeyi doldurur. Yol, birbiriyle bağlantısız birkaç alt yoldan oluşuyorsa, birlikte düşünüldüğünde tüm alt yolların içini doldurur. Bu yöntem, geçerli yolu sonlandırır. |
| [FillText](../../aspose.svg.rendering/idevice/filltext)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| [Flush](../../aspose.svg.rendering/idevice/flush)() | Çıkış akışına tüm verileri temizler. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto)(PointF) | Geçerli noktadan noktaya (pt) düz bir çizgi parçası ekler. Yeni geçerli nokta pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak ve herhangi bir bağlantı çizgisi parçasını atlayarak yeni bir alt yolu başlatır. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" bunu geçersiz kılar; yolda önceki "Taşı" işleminden hiçbir iz kalmıyor. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext)() | Yığından çıkararak tüm grafik bağlamını eski değerine geri yükler. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext)() | Tüm grafik içeriğinin bir kopyasını yığına gönderir. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya eğri parçayı takip eder, kenarları ona paralel olacak şekilde parça üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem, geçerli yolu sonlandırır. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill)(FillMode) | Geçerli yolu konturlar ve doldurur. Bu yöntem, geçerli yolu sonlandırır. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext)(string, PointF) | Belirtilen metin dizesini belirtilen konumda konturlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Svg.Rendering](../../aspose.svg.rendering)
* toplantı [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
