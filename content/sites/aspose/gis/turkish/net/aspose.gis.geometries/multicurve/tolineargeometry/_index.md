---
title: ToLinearGeometry
second_title: Aspose.GIS for .NET API Referansı
description: Belirtilen geometriyi kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alırhata payı .
type: docs
weight: 70
url: /tr/net/aspose.gis.geometries/multicurve/tolineargeometry/
---
## ToLinearGeometry(double) {#tolineargeometry_5}

Belirtilen geometriyi kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` .

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| tolerance | Double | `hata payı`kullanmak. sonucun daha az olması garanti edilir.`hata payı` geometriyi doğrusallaştırmak için gereken nokta sayısı kadran başına maksimum değeri aşmadıkça, kavisli geometriden uzak, şu anda 10000 noktaya eşittir. |

### Geri dönüş değeri

A[`IMultiLineString`](../../imultilinestring) buna yaklaşan veya buna eşdeğer[`IMultiCurve`](../../imulticurve) :  Bu nesne ise[`IMultiLineString`](../../imultilinestring) sonuç bu nesneye eşdeğerdir Bu nesne değilse[`IMultiLineString`](../../imultilinestring) - tüm eğriler doğrusallaştırılmış ve yeni`IMultiLineString` oluşturuldu

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | `hata payı` küçük veya eşittir`0` . |
| InvalidOperationException | Bu geometri, işlem tamamlanamayacak şekilde geçersizdir. |

### Ayrıca bakınız

* interface [IMultiLineString](../../imultilinestring)
* class [MultiCurve](../../multicurve)
* ad alanı [Aspose.Gis.Geometries](../../multicurve)
* toplantı [Aspose.GIS](../../../)

---

## ToLinearGeometry() {#tolineargeometry_4}

Varsayılanı kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` .

```csharp
public IMultiLineString ToLinearGeometry()
```

### Geri dönüş değeri

A[`IMultiLineString`](../../imultilinestring) buna yaklaşan veya buna eşdeğer[`IMultiCurve`](../../imulticurve). Bu eşdeğerdir[`ToLinearGeometry`](../../imulticurve/tolineargeometry) with varsayılan`hata payı` . Varsayılan`hata payı` s değeri bağlıdır[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) bu geometrinin:  Öngörülen SRS Toleransı için 0,001 metredir (SRS birimlerinde) Coğrafi SRS Toleransı için`1e-5` derece (SRS birimlerinde) Bilinmeyen SRS Toleransı için`1e-5` Hangi dönüşümlerin uygulandığı hakkında daha fazla ayrıntı için bkz.[`ToLinearGeometry`](../../imulticurve/tolineargeometry) belirtim.

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | Bu geometri, işlem tamamlanamayacak şekilde geçersizdir. |

### Ayrıca bakınız

* interface [IMultiLineString](../../imultilinestring)
* class [MultiCurve](../../multicurve)
* ad alanı [Aspose.Gis.Geometries](../../multicurve)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
