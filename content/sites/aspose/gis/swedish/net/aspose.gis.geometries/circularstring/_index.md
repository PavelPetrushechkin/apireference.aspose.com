---
title: CircularString
second_title: Aspose.GIS för .NET API Referens
description: En kurva med flera vertex med cirkulär interpolation mellan punkter.
type: docs
weight: 780
url: /sv/net/aspose.gis.geometries/circularstring/
---
## CircularString class

En kurva med flera vertex med cirkulär interpolation mellan punkter.

```csharp
public class CircularString : Curve, ICircularString
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CircularString](circularstring#constructor)() | Initierar en ny instans av[`CircularString`](../circularstring) class. |
| [CircularString](circularstring#constructor_1)(ICircularString) | Initierar en ny instans av[`CircularString`](../circularstring) class. |
| [CircularString](circularstring#constructor_2)(IEnumerable&lt;IPoint&gt;) | Initierar en ny instans av[`CircularString`](../circularstring) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension) { get; } | Hämtar antalet koordinatdimensioner för detta[`Geometry`](../geometry) . |
| [Count](../../aspose.gis.geometries/circularstring/count) { get; } | Får antalet poäng i[`CircularString`](../circularstring) . |
| [Dimension](../../aspose.gis.geometries/curve/dimension) { get; } | Får den topologiska dimensionen av detta[`Geometry`](../geometry) . |
| override [EndPoint](../../aspose.gis.geometries/circularstring/endpoint) { get; } | Returnerar en kopia av kurvans slutpunkt. |
| override [GeometryType](../../aspose.gis.geometries/circularstring/geometrytype) { get; } | Hämtar typen av geometri. |
| override [HasCurveGeometry](../../aspose.gis.geometries/circularstring/hascurvegeometry) { get; } | Får ett värde som indikerar om denna geometri är eller innehåller kurvgeometri (ej linjär). |
| [HasM](../../aspose.gis.geometries/circularstring/hasm) { get; set; } | Får ett värde som indikerar om denna instans har M-koordinat. |
| [HasZ](../../aspose.gis.geometries/circularstring/hasz) { get; set; } | Får ett värde som indikerar om denna instans har Z-koordinat. |
| [IsClosed](../../aspose.gis.geometries/curve/isclosed) { get; } | Får ett värde som indikerar om en kurva är stängd. En kurva stängs om dess startpunkt är lika med dess slutpunkt. |
| override [IsEmpty](../../aspose.gis.geometries/circularstring/isempty) { get; } | Får ett värde som anger om denna instans är tom. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple) { get; } | Får ett värde som indikerar om denna instans är enkel ur SFA-synpunkt. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid) { get; } | Får ett värde som indikerar om denna instans är giltig. |
| [Item](../../aspose.gis.geometries/circularstring/item) { get; set; } | Hämtar eller ställer in[`IPoint`](../ipoint) vid angivet index. |
| [SpatialReferenceSystem](../../aspose.gis.geometries/circularstring/spatialreferencesystem) { get; set; } | Hämtar SpatialReferenceSystem för denna instans. Den här egenskapen kan vara`null` , om SpatialReferenceSystem inte är inställt. Att tilldela nytt SpatialReferenceSystem kommer inte att utföra någon koordinattransformation, endast referensen kommer att ändras. |
| override [StartPoint](../../aspose.gis.geometries/circularstring/startpoint) { get; } | Returnerar en kopia av startpunkten för kurvan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint#addpoint)(IPoint) | Lägger till en punkt i slutet av den cirkulära strängen. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint#addpoint_1)(double, double) | Lägger till en punkt i slutet av den cirkulära strängen. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint#addpoint_2)(double, double, double) | Lägger till en punkt i slutet av den cirkulära strängen. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint#addpoint_3)(double, double, double, double) | Lägger till en punkt i slutet av den cirkulära strängen. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary)() | Översätter denna geometri till dess välkända binära representation. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary)(WkbVariant) | Översätter denna geometri till dess välkända binära representation. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | Exportera denna geometri till en bildrepresentation. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | Exportera denna geometri till en bildrepresentation. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | Exportera denna geometri till en bildrepresentation. |
| [AsText](../../aspose.gis.geometries/geometry/astext)() | Översätter denna geometri till dess välkända textrepresentation. |
| [AsText](../../aspose.gis.geometries/geometry/astext)(WktVariant) | Översätter denna geometri till dess välkända textrepresentation. |
| [AsText](../../aspose.gis.geometries/geometry/astext)(WktVariant, NumericFormat) | Översätter denna geometri till dess välkända textrepresentation. |
| override [Clone](../../aspose.gis.geometries/circularstring/clone)() | Klonar den här instansen. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby)(IGeometry) | Bestämmer om denna geometri täcks av en specificerad geometri. |
| [Covers](../../aspose.gis.geometries/geometry/covers)(IGeometry) | Bestämmer om denna geometri täcker en specificerad geometri. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses)(IGeometry) | Bestämmer om denna geometri och en specificerad geometri korsar. |
| [Difference](../../aspose.gis.geometries/geometry/difference)(IGeometry) | Subtraherar en specificerad geometri från denna geometri. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint)(IGeometry) | Bestämmer om denna geometri är osammanhängande från en specificerad geometri. |
| [Equals](../../aspose.gis.geometries/circularstring/equals#equals)(ICircularString) | Anger om det aktuella objektet är lika med ett annat objekt av samma typ. |
| override [Equals](../../aspose.gis.geometries/circularstring/equals#equals_1)(object) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea)() | Beräknar arean av denna geometri. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer)(double, int) | Beräknar ett buffertområde runt denna geometri. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid)() | Beräknar tyngdpunkten för denna geometri. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull)() | Beräknar det konvexa skrovet för denna geometri. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto)(IGeometry) | Beräknar det minsta avståndet mellan denna geometri och en specificerad geometri. |
| [GetEnumerator](../../aspose.gis.geometries/circularstring/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent)() | Beräknar och returnerar en avgränsande utsträckning av denna geometri. |
| override [GetHashCode](../../aspose.gis.geometries/circularstring/gethashcode)() | Fungerar som standard hash-funktion. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength)() | Beräknar längden på denna geometri. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection)(IGeometry) | Bygger en skärningspunkt mellan denna geometri och en specificerad geometri. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects)(Extent) | Bestämmer om denna geometri skär en specificerad utsträckning. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects)(IGeometry) | Bestämmer om denna geometri och en specificerad geometri skär varandra. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps)(IGeometry) | Bestämmer om denna geometri överlappar med en specificerad geometri. |
| [Relate](../../aspose.gis.geometries/geometry/relate)(IGeometry, string) | Bestämmer om DE-9IM skärningsmatris för denna geometri och en specificerad geometri matchar det angivna mönstret. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines)() | Får polygoner representerade som linjer i denna geometri. |
| override [Reverse](../../aspose.gis.geometries/circularstring/reverse)() | Omvänd ordning på punkterna i detta[`CircularString`](../circularstring) . |
| [RoundM](../../aspose.gis.geometries/geometry/roundm)(int) | Avrundar M-koordinaten till ett angivet antal bråksiffror. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy)(int) | Avrundar X- och Y-koordinaterna till ett specificerat antal bråksiffror. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz)(int) | Avrundar Z-koordinaten till ett specificerat antal bråksiffror. |
| override [SetEmpty](../../aspose.gis.geometries/circularstring/setempty)() | gör detta[`Geometry`](../geometry) tomt. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains)(IGeometry) | Bestämmer om denna geometri rymdmässigt innehåller en specificerad geometri. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals)(IGeometry) | Bestämmer om denna geometri är rumsligt lika med en specificerad geometri. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference)(IGeometry) | Bygger en symmetrisk skillnad mellan denna geometri och en specificerad geometri. |
| [ToEditable](../../aspose.gis.geometries/circularstring/toeditable#toeditable)() | Får en redigerbar kopia av denna geometri. (3 methods) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable)() | Får en redigerbar kopia av denna geometri. |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry)() | Får ungefärlig eller likvärdig icke-kurv version av denna geometri med standard`tolerans` . (2 methods) |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry)(double) | Får ungefärlig eller likvärdig icke-kurv version av denna geometri med den angivna`tolerans` . (2 methods) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [Touches](../../aspose.gis.geometries/geometry/touches)(IGeometry) | Bestämmer om denna geometri och en specificerad geometri berör. |
| [Union](../../aspose.gis.geometries/geometry/union)(IGeometry) | Förenar denna geometri och en specificerad geometri. |
| [Within](../../aspose.gis.geometries/geometry/within)(Extent) | Bestämmer om denna geometri är inom en specificerad omfattning. |
| [Within](../../aspose.gis.geometries/geometry/within)(IGeometry) | Bestämmer om denna geometri är inom en specificerad geometri. |
| [operator ==](../../aspose.gis.geometries/circularstring/op_equality) | Implementerar operatorn ==. |
| [operator !=](../../aspose.gis.geometries/circularstring/op_inequality) | Implementerar operatorn !=. |

### Anmärkningar

Den`CircularString` består av ett eller flera cirkelbågssegment anslutna ände till ände. De första tre punkterna definierar det första segmentet. Den första punkten är startpunkten för bågen. Den andra punkten är vilken som helst mellanpunkt på bågen förutom start- eller slutpunkten. Den tredje punkten är slutet av bågen. Efterföljande bågar definieras endast av deras mellanliggande och slutpunkter, eftersom startpunkten implicit definieras som det föregående segmentets slutpunkt.

### Se även

* class [Curve](../curve)
* interface [ICircularString](../icircularstring)
* namnutrymme [Aspose.Gis.Geometries](../../aspose.gis.geometries)
* hopsättning [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
