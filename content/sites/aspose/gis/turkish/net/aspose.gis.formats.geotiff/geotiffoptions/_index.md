---
title: GeoTiffOptions
second_title: Aspose.GIS for .NET API Referansı
description: GeoTiff formatı için sürücüye özel seçenekler.
type: docs
weight: 280
url: /tr/net/aspose.gis.formats.geotiff/geotiffoptions/
---
## GeoTiffOptions class

GeoTiff formatı için sürücüye özel seçenekler.

```csharp
public class GeoTiffOptions : RasterDriverOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GeoTiffOptions](geotiffoptions)() | Yeni örnek oluştur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | Kapatılmamış birLinearRing her geometride Varsayılan`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | Her geometri parçasının ortasına yeni bir nokta eklenip eklenmeyeceğini belirler. Varsayılan`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | Her geometrideki yakın noktaların silinip silinmeyeceğini belirler. Varsayılan`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | için mesafeyi belirler[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints) . Varsayılan`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | Eğri geometrilerini doğrusallaştırmak için kullanılacak bir tolerans. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel) geometriler eklendiğinde M koordinat öğesine uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | için mesafeyi belirler[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments) . Varsayılan`0` . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | Katmana eklendiklerinde geometrilerin doğrulanıp doğrulanmayacağını belirler. olarak ayarlanırsa`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)katmana eklendiğinde ve doğrulama başarısız olursa her geometrisi için çağrılır ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid) dır-dir`false` ),[`GisException`](../../aspose.gis/gisexception) atılır. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | Çokgenin veya çok çokgenin çizgi dizisine dönüştürülmesine izin verilip verilmediğini belirler. Varsayılan`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)geometriler eklendiğinde X ve Y koordinatlarına uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel) geometriler eklendiğinde Z koordinat öğesine uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |

### Ayrıca bakınız

* class [RasterDriverOptions](../../aspose.gis/rasterdriveroptions)
* ad alanı [Aspose.Gis.Formats.GeoTiff](../../aspose.gis.formats.geotiff)
* toplantı [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
