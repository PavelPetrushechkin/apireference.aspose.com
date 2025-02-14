---
title: GetDistanceTo
second_title: Referencia de API de Aspose.GIS para .NET
description: Calcula la distancia mínima entre esta geometría y una geometría especificada.
type: docs
weight: 240
url: /es/net/aspose.gis.geometries/geometry/getdistanceto/
---
## Geometry.GetDistanceTo method

Calcula la distancia mínima entre esta geometría y una geometría especificada.

```csharp
public double GetDistanceTo(IGeometry other)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| other | IGeometry | Una geometría para encontrar la distancia a. |

### Valor_devuelto

Si ambas geometrías no son[`IsEmpty`](../isempty) - una distancia entre los puntos más cercanos de las geometrías. Si al menos una geometría está vacía, se devuelve -1.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El argumento es`null`. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) de geometrías no son equivalentes. Puede utilizar[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) para convertir geometrías al mismo sistema de referencia espacial . |

### Ver también

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* espacio de nombres [Aspose.Gis.Geometries](../../geometry)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
