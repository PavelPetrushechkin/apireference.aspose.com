---
title: Difference
second_title: Aspose.GIS för .NET API Referens
description: Subtraherar en specificerad geometri från denna geometri.
type: docs
weight: 180
url: /sv/net/aspose.gis.geometries/geometry/difference/
---
## Geometry.Difference method

Subtraherar en specificerad geometri från denna geometri.

```csharp
public IGeometry Difference(IGeometry other)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | IGeometry | En geometri att subtrahera. |

### Returvärde

En geometri som representerar en skillnad mellan denna geometri och ett argument. Resultatgeometrin innehåller punktuppsättning som finns i denna geometri men som inte finns i ett argument.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *other* är`null`. |
| ArgumentException | En av geometrierna är ogiltig på ett sådant sätt att operationen inte kan avslutas. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) av geometrier är inte likvärdiga. Du kan använda[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) för att konvertera geometrier till samma rumsliga referenssystem. |

### Se även

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* namnutrymme [Aspose.Gis.Geometries](../../geometry)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
