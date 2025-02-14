---
title: LinearRing
second_title: Aspose.GIS für .NET-API-Referenz
description: ALinearRing./linearring ist einLineString./linestring das ist sowohl geschlossen als auch einfach.
type: docs
weight: 1030
url: /de/net/aspose.gis.geometries/linearring/
---
## LinearRing class

A[`LinearRing`](../linearring) ist ein[`LineString`](../linestring) das ist sowohl geschlossen als auch einfach.

```csharp
public class LinearRing : LineString, ILinearRing
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LinearRing](linearring#constructor)() | Initialisiert eine neue Instanz von[`LinearRing`](../linearring) Klasse. |
| [LinearRing](linearring#constructor_2)(IEnumerable&lt;IPoint&gt;) | Initialisiert eine neue Instanz von[`LinearRing`](../linearring) Klasse. |
| [LinearRing](linearring#constructor_1)(ILineString) | Initialisiert eine neue Instanz von[`LinearRing`](../linearring) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension) { get; } | Liefert die Anzahl der Koordinatendimensionen dafür[`Geometry`](../geometry) . |
| [Count](../../aspose.gis.geometries/linestring/count) { get; } | Ruft die Anzahl der Punkte in der ab[`LineString`](../linestring) . |
| [Dimension](../../aspose.gis.geometries/curve/dimension) { get; } | Ruft die topologische Dimension davon ab[`Geometry`](../geometry) . |
| override [EndPoint](../../aspose.gis.geometries/linestring/endpoint) { get; } | Gibt eine Kopie des Endpunkts der Kurve zurück. |
| override [GeometryType](../../aspose.gis.geometries/linearring/geometrytype) { get; } | Ruft den Typ der Geometrie ab. |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry) { get; } | Ruft einen Wert ab, der angibt, ob diese Geometrie Kurvengeometrie (nicht linear) ist oder enthält. |
| [HasM](../../aspose.gis.geometries/linestring/hasm) { get; set; } | Ruft einen Wert ab, der angibt, ob diese Instanz eine M-Koordinate hat. |
| [HasZ](../../aspose.gis.geometries/linestring/hasz) { get; set; } | Ruft einen Wert ab, der angibt, ob diese Instanz eine Z-Koordinate hat. |
| [IsClosed](../../aspose.gis.geometries/curve/isclosed) { get; } | Ruft einen Wert ab, der angibt, ob eine Kurve geschlossen ist. Eine Kurve ist geschlossen, wenn ihr Anfangspunkt gleich ihrem Endpunkt ist. |
| override [IsEmpty](../../aspose.gis.geometries/linestring/isempty) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz leer ist. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz aus SFA-Sicht einfach ist. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz gültig ist. |
| [Item](../../aspose.gis.geometries/linestring/item) { get; set; } | Ruft ab oder setzt die[`IPoint`](../ipoint) am angegebenen Index. |
| [SpatialReferenceSystem](../../aspose.gis.geometries/linestring/spatialreferencesystem) { get; set; } | Ruft SpatialReferenceSystem dieser Instanz ab. Diese Eigenschaft kann sein`null` , wenn SpatialReferenceSystem nicht gesetzt ist. Bei der Zuweisung eines neuen SpatialReferenceSystem wird keine Koordinatentransformation durchgeführt, nur die Referenz ändert sich. |
| override [StartPoint](../../aspose.gis.geometries/linestring/startpoint) { get; } | Gibt eine Kopie des Startpunkts der Kurve zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint)(IPoint) | Fügt einen Punkt am Ende der Linie hinzu. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint)(double, double) | Fügt einen Punkt am Ende der Linie hinzu. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint)(double, double, double) | Fügt einen Punkt am Ende der Linie hinzu. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint)(double, double, double, double) | Fügt einen Punkt am Ende der Linie hinzu. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary)() | Übersetzt diese Geometrie in ihre bekannte binäre Darstellung. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary)(WkbVariant) | Übersetzt diese Geometrie in ihre bekannte binäre Darstellung. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | Exportieren Sie diese Geometrie in eine Bilddarstellung. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | Exportieren Sie diese Geometrie in eine Bilddarstellung. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | Exportieren Sie diese Geometrie in eine Bilddarstellung. |
| [AsText](../../aspose.gis.geometries/geometry/astext)() | Übersetzt diese Geometrie in ihre bekannte Textdarstellung. |
| [AsText](../../aspose.gis.geometries/geometry/astext)(WktVariant) | Übersetzt diese Geometrie in ihre bekannte Textdarstellung. |
| [AsText](../../aspose.gis.geometries/geometry/astext)(WktVariant, NumericFormat) | Übersetzt diese Geometrie in ihre bekannte Textdarstellung. |
| override [Clone](../../aspose.gis.geometries/linearring/clone)() | Klont diese Instanz. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby)(IGeometry) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie abgedeckt wird. |
| [Covers](../../aspose.gis.geometries/geometry/covers)(IGeometry) | Bestimmt, ob diese Geometrie eine bestimmte Geometrie abdeckt. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses)(IGeometry) | Bestimmt, ob sich diese Geometrie und eine angegebene Geometrie kreuzen. |
| [Difference](../../aspose.gis.geometries/geometry/difference)(IGeometry) | Subtrahiert eine angegebene Geometrie von dieser Geometrie. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint)(IGeometry) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie disjunkt ist. |
| [Equals](../../aspose.gis.geometries/linestring/equals)(ILineString) | Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt desselben Typs ist. |
| override [Equals](../../aspose.gis.geometries/linestring/equals)(object) | Bestimmt, ob das angegebene Objekt gleich dem aktuellen Objekt ist. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea)() | Berechnet die Fläche dieser Geometrie. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer)(double, int) | Berechnet einen Pufferbereich um diese Geometrie herum. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid)() | Berechnet den Schwerpunkt dieser Geometrie. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull)() | Berechnet die konvexe Hülle dieser Geometrie. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto)(IGeometry) | Berechnet den Mindestabstand zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [GetEnumerator](../../aspose.gis.geometries/linestring/getenumerator)() | Gibt einen Enumerator zurück, der die Auflistung durchläuft. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent)() | Berechnet und gibt eine Begrenzungsausdehnung dieser Geometrie zurück. |
| override [GetHashCode](../../aspose.gis.geometries/linestring/gethashcode)() | Dient als Standard-Hash-Funktion. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength)() | Berechnet die Länge dieser Geometrie. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection)(IGeometry) | Erstellt einen Schnittpunkt zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects)(Extent) | Bestimmt, ob diese Geometrie eine bestimmte Ausdehnung schneidet. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects)(IGeometry) | Bestimmt, ob sich diese Geometrie und eine angegebene Geometrie schneiden. |
| [IsClockwise](../../aspose.gis.geometries/linearring/isclockwise)() | Bestimmt, ob der Ring im Uhrzeigersinn gewickelt ist. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps)(IGeometry) | Bestimmt, ob sich diese Geometrie mit einer bestimmten Geometrie überschneidet. |
| [Relate](../../aspose.gis.geometries/geometry/relate)(IGeometry, string) | Bestimmt, ob die DE-9IM-Schnittpunktmatrix dieser Geometrie und einer bestimmten Geometrie mit dem bereitgestellten Muster übereinstimmt. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines)() | Ruft Polygone ab, die als Linien dieser Geometrie dargestellt werden. |
| override [Reverse](../../aspose.gis.geometries/linestring/reverse)() | Kehrt die Reihenfolge der Punkte um[`LineString`](../linestring) . |
| [RoundM](../../aspose.gis.geometries/geometry/roundm)(int) | Rundet die M-Koordinate auf eine angegebene Anzahl von Nachkommastellen. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy)(int) | Rundet X- und Y-Koordinaten auf eine angegebene Anzahl von Nachkommastellen. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz)(int) | Rundet die Z-Koordinate auf eine angegebene Anzahl von Nachkommastellen. |
| override [SetEmpty](../../aspose.gis.geometries/linestring/setempty)() | Macht das[`Geometry`](../geometry) leer. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains)(IGeometry) | Bestimmt, ob diese Geometrie räumlich eine bestimmte Geometrie enthält. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals)(IGeometry) | Bestimmt, ob diese Geometrie räumlich gleich einer bestimmten Geometrie ist. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference)(IGeometry) | Erstellt eine symmetrische Differenz zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [ToEditable](../../aspose.gis.geometries/linearring/toeditable#toeditable_2)() | Ruft eine bearbeitbare Kopie dieser Geometrie ab. (4 methods) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable)() | Ruft eine bearbeitbare Kopie dieser Geometrie ab. |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry)() | Ruft eine ungefähre oder äquivalente Nicht-Kurven-Version dieser Geometrie unter Verwendung der Vorgabe ab`Toleranz` . (2 methods) |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry)(double) | Ruft eine ungefähre oder äquivalente Nicht-Kurven-Version dieser Geometrie unter Verwendung der angegebenen ab`Toleranz` . (2 methods) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| [Touches](../../aspose.gis.geometries/geometry/touches)(IGeometry) | Bestimmt, ob sich diese Geometrie und eine bestimmte Geometrie berühren. |
| [Union](../../aspose.gis.geometries/geometry/union)(IGeometry) | Vereint diese Geometrie und eine angegebene Geometrie. |
| [Within](../../aspose.gis.geometries/geometry/within)(Extent) | Bestimmt, ob sich diese Geometrie innerhalb einer bestimmten Ausdehnung befindet. |
| [Within](../../aspose.gis.geometries/geometry/within)(IGeometry) | Bestimmt, ob diese Geometrie innerhalb einer angegebenen Geometrie liegt. |

### Siehe auch

* class [LineString](../linestring)
* interface [ILinearRing](../ilinearring)
* namensraum [Aspose.Gis.Geometries](../../aspose.gis.geometries)
* Montage [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
