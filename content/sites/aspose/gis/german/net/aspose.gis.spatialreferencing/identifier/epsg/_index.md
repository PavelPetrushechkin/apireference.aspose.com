---
title: Epsg
second_title: Aspose.GIS für .NET-API-Referenz
description: Erstellt eine neue Kennung die die EPSGKennung mit Code darstelltepsgCode .
type: docs
weight: 20
url: /de/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

Erstellt eine neue Kennung, die die EPSG-Kennung mit Code darstellt*epsgCode* .

```csharp
public static Identifier Epsg(int epsgCode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| epsgCode | Int32 | Epsg-Code. |

### Rückgabewert

Neue Kennung mit[`AuthorityName`](../authorityname) "EPSG" und[`AuthorityUniqueIdentifier`](../authorityuniqueidentifier)*epsgCode* . Wenn*epsgCode* ist kleiner als 0 - zurück`null` ;

### Siehe auch

* class [Identifier](../../identifier)
* namensraum [Aspose.Gis.SpatialReferencing](../../identifier)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
