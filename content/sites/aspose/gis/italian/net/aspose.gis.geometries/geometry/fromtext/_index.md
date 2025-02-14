---
title: FromText
second_title: Riferimento API Aspose.GIS per .NET
description: Crea una geometria dalla sua rappresentazione di testo noto.
type: docs
weight: 470
url: /it/net/aspose.gis.geometries/geometry/fromtext/
---
## FromText(string) {#fromtext}

Crea una geometria dalla sua rappresentazione di testo noto.

```csharp
public static IGeometry FromText(string wkt)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wkt | String | Rappresentazione testuale ben nota di una geometria. |

### Valore di ritorno

Una geometria rappresentata dall'argomento.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è nullo. |
| NotSupportedException | L'argomento rappresenta una geometria di tipo non supportato. |
| FormatException | L'argomento non è un testo noto valido. |

### Guarda anche

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

---

## FromText(string, SpatialReferenceSystem) {#fromtext_1}

Crea una geometria dalla sua rappresentazione di testo noto.

```csharp
public static IGeometry FromText(string wkt, SpatialReferenceSystem spatialReferenceSystem)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wkt | String | Rappresentazione testuale ben nota di una geometria. |
| spatialReferenceSystem | SpatialReferenceSystem | Sistema di riferimento spaziale da assegnare alla geometria. |

### Valore di ritorno

Una geometria rappresentata dall'argomento.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è nullo. |
| NotSupportedException | L'argomento rappresenta una geometria di tipo non supportato. |
| FormatException | L'argomento non è un testo noto valido. |

### Guarda anche

* interface [IGeometry](../../igeometry)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
