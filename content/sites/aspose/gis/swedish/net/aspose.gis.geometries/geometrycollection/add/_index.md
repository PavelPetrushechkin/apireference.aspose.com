---
title: Add
second_title: Aspose.GIS för .NET API Referens
description: Lägger till den angivna geometrin till samlingen.
type: docs
weight: 110
url: /sv/net/aspose.gis.geometries/geometrycollection/add/
---
## GeometryCollection.Add method

Lägger till den angivna geometrin till samlingen.

```csharp
public void Add(IGeometry geometry)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometry | IGeometry | Geometrin att lägga till. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Argumentet är`null`. |
| ArgumentException | Samlingen accepterar inte geometrier av denna typ. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) av denna geometri och[`SpatialReferenceSystem`](../spatialreferencesystem) av argument är båda not `null` och inte är lika med varandra. |

### Se även

* interface [IGeometry](../../igeometry)
* class [GeometryCollection](../../geometrycollection)
* namnutrymme [Aspose.Gis.Geometries](../../geometrycollection)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
