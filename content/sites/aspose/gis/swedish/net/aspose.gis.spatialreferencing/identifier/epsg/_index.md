---
title: Epsg
second_title: Aspose.GIS för .NET API Referens
description: Skapar en ny identifierare som representerar EPSGidentifierare med kodepsgCode .
type: docs
weight: 20
url: /sv/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

Skapar en ny identifierare som representerar EPSG-identifierare med kod*epsgCode* .

```csharp
public static Identifier Epsg(int epsgCode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| epsgCode | Int32 | Epsg-kod. |

### Returvärde

Ny identifierare med[`AuthorityName`](../authorityname) "EPSG" och[`AuthorityUniqueIdentifier`](../authorityuniqueidentifier)*epsgCode* . Om*epsgCode* är mindre än 0 - retur`null` ;

### Se även

* class [Identifier](../../identifier)
* namnutrymme [Aspose.Gis.SpatialReferencing](../../identifier)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
