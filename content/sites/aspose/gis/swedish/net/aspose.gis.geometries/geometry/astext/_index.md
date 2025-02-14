---
title: AsText
second_title: Aspose.GIS för .NET API Referens
description: Översätter denna geometri till dess välkända textrepresentation.
type: docs
weight: 130
url: /sv/net/aspose.gis.geometries/geometry/astext/
---
## AsText() {#astext}

Översätter denna geometri till dess välkända textrepresentation.

```csharp
public string AsText()
```

### Returvärde

Välkänd textrepresentation av denna geometri.

### Anmärkningar

Utdata från denna metod är inIso WKT variant. Det numeriska standardformatet är[`General`](../../../aspose.gis/numericformat/general) (med "0"-precision).

### Se även

* class [Geometry](../../geometry)
* namnutrymme [Aspose.Gis.Geometries](../../geometry)
* hopsättning [Aspose.GIS](../../../)

---

## AsText(WktVariant) {#astext_1}

Översätter denna geometri till dess välkända textrepresentation.

```csharp
public string AsText(WktVariant variant)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variant | WktVariant | Välkänd textvariant att använda. |

### Returvärde

Välkänd textrepresentation av denna geometri.

### Undantag

| undantag | skick |
| --- | --- |
| NotSupportedException | Geometri kan inte representeras i begärd WKT-variant. För närvarande händer detta när [`HasCurveGeometry`](../hascurvegeometry) av geometri är`true` och WKT-varianten är SimpleFeatureAccessOutdated . |
| ArgumentOutOfRangeException | *variant* är inte en giltig[`WktVariant`](../../wktvariant). |

### Anmärkningar

Det numeriska standardformatet är[`General`](../../../aspose.gis/numericformat/general) (med "0"-precision).

### Se även

* enum [WktVariant](../../wktvariant)
* class [Geometry](../../geometry)
* namnutrymme [Aspose.Gis.Geometries](../../geometry)
* hopsättning [Aspose.GIS](../../../)

---

## AsText(WktVariant, NumericFormat) {#astext_2}

Översätter denna geometri till dess välkända textrepresentation.

```csharp
public string AsText(WktVariant variant, NumericFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variant | WktVariant | Välkänd textvariant att använda. |
| format | NumericFormat | Koordinatformat för konvertering till sträng. Se den[`NumericFormat`](../../../aspose.gis/numericformat) att få det. |

### Returvärde

Välkänd textrepresentation av denna geometri.

### Undantag

| undantag | skick |
| --- | --- |
| NotSupportedException | Geometri kan inte representeras i begärd WKT-variant. För närvarande händer detta när [`HasCurveGeometry`](../hascurvegeometry) av geometri är`true` och WKT-varianten är SimpleFeatureAccessOutdated . |
| ArgumentOutOfRangeException | *variant* är inte en giltig[`WktVariant`](../../wktvariant). |

### Se även

* enum [WktVariant](../../wktvariant)
* class [NumericFormat](../../../aspose.gis/numericformat)
* class [Geometry](../../geometry)
* namnutrymme [Aspose.Gis.Geometries](../../geometry)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
