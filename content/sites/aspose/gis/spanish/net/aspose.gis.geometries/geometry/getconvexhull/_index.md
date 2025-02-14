---
title: GetConvexHull
second_title: Referencia de API de Aspose.GIS para .NET
description: Calcula el casco convexo de esta geometría.
type: docs
weight: 230
url: /es/net/aspose.gis.geometries/geometry/getconvexhull/
---
## Geometry.GetConvexHull method

Calcula el casco convexo de esta geometría.

```csharp
public IGeometry GetConvexHull()
```

### Valor_devuelto

Una geometría que representa un casco convexo de esta geometría. Si esta geometría no tiene puntos, el resultado es[`Null`](../null) . Si esta geometría tiene solo un punto, el resultado es este punto. Si esta geometría tiene solo dos puntos, el resultado es[`ILineString`](../../ilinestring) con los puntos. Si esta geometría tiene tres o más puntos entonces el resultado es[`ILinearRing`](../../ilinearring) que representa un casco convexo alrededor de todos los puntos de geometría.

### Ver también

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* espacio de nombres [Aspose.Gis.Geometries](../../geometry)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
