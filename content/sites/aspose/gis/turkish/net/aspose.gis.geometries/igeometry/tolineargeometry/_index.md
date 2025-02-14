---
title: ToLinearGeometry
second_title: Aspose.GIS for .NET API Referansı
description: Varsayılanı kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alırhata payı .
type: docs
weight: 350
url: /tr/net/aspose.gis.geometries/igeometry/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

Varsayılanı kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` .

```csharp
public IGeometry ToLinearGeometry()
```

### Geri dönüş değeri

Eğri geometrisi olmayan bir geometri. Bu eşdeğerdir[`ToLinearGeometry`](../tolineargeometry) with varsayılan`hata payı` . Varsayılan`hata payı` tarafından tanımlanır[`SpatialReferenceSystem`](../spatialreferencesystem) bu geometrinin:  Öngörülen SRS Toleransı için 0,001 metredir (SRS birimlerinde) Coğrafi SRS Toleransı için`1e-5` derece (SRS birimlerinde) Bilinmeyen SRS Toleransı için`1e-5` Hangi dönüşümlerin uygulandığı hakkında daha fazla ayrıntı için bkz.[`ToLinearGeometry`](../tolineargeometry) belirtim.

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | Bu geometri, işlem tamamlanamayacak şekilde geçersizdir. |

### Ayrıca bakınız

* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

Belirtilen geometriyi kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` .

```csharp
public IGeometry ToLinearGeometry(double tolerance)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| tolerance | Double | `hata payı`kullanmak. sonucun daha az olması garanti edilir.`hata payı` geometriyi doğrusallaştırmak için gereken nokta sayısı, şu anda 10000 noktaya eşit olan kadran başına maksimum değerini aşmadığı sürece, eğri geometriden uzakta. |

### Geri dönüş değeri

Eğri geometrisi olmayan bir geometri. Aşağıdaki dönüşümler uygulanır: CircularString s doğrusallaştırılmış (dönüştürülmüşLineString s ile belirtilen*tolerance* )CompoundCurve s birleştirilir`Çizgi Dizisi` sCurvePolygon s dönüştürülürPolygon sMultiCurve s dönüştürülürMultiLineString sMultiSurface s dönüştürülürMultiPolygon s Sonuç olarak,[`HasCurveGeometry`](../hascurvegeometry) çıkış geometrisi`false` .

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | `hata payı` küçük veya eşittir`0` . |
| InvalidOperationException | Bu geometri, işlem tamamlanamayacak şekilde geçersizdir. |

### Ayrıca bakınız

* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
