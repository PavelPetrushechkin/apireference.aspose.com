---
title: Difference
second_title: Aspose.GIS für .NET-API-Referenz
description: Subtrahiert eine angegebene Geometrie von dieser Geometrie.
type: docs
weight: 180
url: /de/net/aspose.gis.geometries/geometry/difference/
---
## Geometry.Difference method

Subtrahiert eine angegebene Geometrie von dieser Geometrie.

```csharp
public IGeometry Difference(IGeometry other)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | IGeometry | Eine zu subtrahierende Geometrie. |

### Rückgabewert

Eine Geometrie, die einen Unterschied zwischen dieser Geometrie und einem Argument darstellt. Die Ergebnisgeometrie enthält Punktsätze, die in dieser Geometrie, aber nicht in einem Argument vorhanden sind.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *other* ist`null`. |
| ArgumentException | Eine der Geometrien ist ungültig, sodass der Vorgang nicht abgeschlossen werden kann. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) von Geometrien sind nicht gleichwertig. Sie können verwenden[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) um Geometrien in dasselbe räumliche Bezugssystem umzuwandeln. |

### Siehe auch

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* namensraum [Aspose.Gis.Geometries](../../geometry)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
