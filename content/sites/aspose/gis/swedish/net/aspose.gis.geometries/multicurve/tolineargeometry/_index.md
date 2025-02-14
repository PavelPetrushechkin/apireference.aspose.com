---
title: ToLinearGeometry
second_title: Aspose.GIS för .NET API Referens
description: Får ungefärlig eller likvärdig ickekurv version av denna geometri med den angivnatolerans .
type: docs
weight: 70
url: /sv/net/aspose.gis.geometries/multicurve/tolineargeometry/
---
## ToLinearGeometry(double) {#tolineargeometry_5}

Får ungefärlig eller likvärdig icke-kurv version av denna geometri med den angivna`tolerans` .

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tolerance | Double | Den`tolerans`att använda. Resultatet blir garanterat mindre än`tolerans` bort från den krökta geometrin, såvida inte antalet punkter som behövs för att linjärisera geometrin överstiger maximivärdet per kvadrant, för närvarande lika med 10000 punkter. |

### Returvärde

A[`IMultiLineString`](../../imultilinestring) som är ungefärlig eller likvärdig med detta[`IMultiCurve`](../../imulticurve) :  Om detta objekt är[`IMultiLineString`](../../imultilinestring) i sig är resultatet ekvivalent med detta objekt Om detta objekt inte är det[`IMultiLineString`](../../imultilinestring) - alla kurvor är linjäriserade och nya`IMultiLineString` är skapad

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | `tolerans` är mindre än eller lika med`0` . |
| InvalidOperationException | Denna geometri är ogiltig på ett sådant sätt att operationen inte kan slutföras. |

### Se även

* interface [IMultiLineString](../../imultilinestring)
* class [MultiCurve](../../multicurve)
* namnutrymme [Aspose.Gis.Geometries](../../multicurve)
* hopsättning [Aspose.GIS](../../../)

---

## ToLinearGeometry() {#tolineargeometry_4}

Får ungefärlig eller likvärdig icke-kurv version av denna geometri med standard`tolerans` .

```csharp
public IMultiLineString ToLinearGeometry()
```

### Returvärde

A[`IMultiLineString`](../../imultilinestring) som är ungefärlig eller likvärdig med detta[`IMultiCurve`](../../imulticurve). Detta är motsvarigheten till[`ToLinearGeometry`](../../imulticurve/tolineargeometry) with default`tolerans` . Standard`tolerans` s värde är beroende av[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) av denna geometri:  För projicerad SRS är toleransen 0,001 meter (i SRS-enheter) För geografisk SRS Tolerans är`1e-5` grader (i SRS-enheter) För okänd SRS Tolerans är`1e-5` Se mer information om vilka transformationer som tillämpas[`ToLinearGeometry`](../../imulticurve/tolineargeometry) specifikation.

### Undantag

| undantag | skick |
| --- | --- |
| InvalidOperationException | Denna geometri är ogiltig på ett sådant sätt att operationen inte kan slutföras. |

### Se även

* interface [IMultiLineString](../../imultilinestring)
* class [MultiCurve](../../multicurve)
* namnutrymme [Aspose.Gis.Geometries](../../multicurve)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
