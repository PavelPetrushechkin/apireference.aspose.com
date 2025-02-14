---
title: GluedShapes
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Devuelve una matriz que contiene los identificadores de las formas que están pegadas a una forma.
type: docs
weight: 780
url: /es/net/aspose.diagram/shape/gluedshapes/
---
## Shape.GluedShapes method

Devuelve una matriz que contiene los identificadores de las formas que están pegadas a una forma.

```csharp
public long[] GluedShapes(GluedShapesFlags flag, string categoryFilter, Shape otherShape)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| flag | GluedShapesFlags | La dimensionalidad y direccionalidad de los puntos de conexión de las formas a devolver. Ver Comentarios para valores posibles[`GluedShapesFlags`](../../gluedshapesflags). |
| categoryFilter | String | Filtra la matriz de ID de formas devueltas limitándola a las ID de formas que coinciden con la categoría especificadaString. |
| otherShape | Shape | Opcional: forma adicional a la que también se deben pegar las formas devueltas, se puede[`Shape`](../../shape) o nulo. |

### Valor_devuelto

matriz de IDInt64.

### Ver también

* enum [GluedShapesFlags](../../gluedshapesflags)
* class [Shape](../../shape)
* espacio de nombres [Aspose.Diagram](../../shape)
* asamblea [Aspose.Diagram](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
