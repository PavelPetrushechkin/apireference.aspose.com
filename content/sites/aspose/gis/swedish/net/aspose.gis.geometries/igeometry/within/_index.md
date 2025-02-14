---
title: Within
second_title: Aspose.GIS för .NET API Referens
description: Bestämmer om denna geometri är inom en specificerad omfattning.
type: docs
weight: 380
url: /sv/net/aspose.gis.geometries/igeometry/within/
---
## Within(Extent) {#within}

Bestämmer om denna geometri är inom en specificerad omfattning.

```csharp
public bool Within(Extent extent)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extent | Extent | Omfattningen. |

### Returvärde

`true` om denna geometri är inom omfattning;`false` annars.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Argument är`null`. |

### Se även

* method [Contains](../../../aspose.gis/extent/contains)
* class [Extent](../../../aspose.gis/extent)
* interface [IGeometry](../../igeometry)
* namnutrymme [Aspose.Gis.Geometries](../../igeometry)
* hopsättning [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

Bestämmer om denna geometri är inom en specificerad geometri.

```csharp
public bool Within(IGeometry other)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | IGeometry | En geometri. |

### Returvärde

`true` om denna geometri är "spatialt inom" en annan geometri.`false` annars.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Argument är`null`. |
| ArgumentException | En av geometrierna är ogiltig på ett sådant sätt att operationen inte kan avslutas. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) av geometrier är inte likvärdiga. Du kan använda[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) för att konvertera geometrier till samma rumsliga referenssystem. |

### Anmärkningar

Denna metod testar om en geometri är inom en annan i termer av DE-9IM skärningsmatris. En geometri är inom en annan, om en annan geometri innehåller varje punkt i geometrin och geometries interiörer skär varandra. Denna metod motsvarar: Se OpenGIS Simple Features Specification för mer information om DE-9IM och "spatially within" relation.

```csharp
this.Relate(other, "T*F**F***");
```

### Se även

* method [SpatiallyContains](../spatiallycontains)
* method [CoveredBy](../coveredby)
* interface [IGeometry](../../igeometry)
* namnutrymme [Aspose.Gis.Geometries](../../igeometry)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
