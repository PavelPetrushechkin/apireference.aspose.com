---
title: Epsg
second_title: Referencia de API de Aspose.GIS para .NET
description: Crea un nuevo identificador que representa el identificador EPSG con códigoepsgCode .
type: docs
weight: 20
url: /es/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

Crea un nuevo identificador que representa el identificador EPSG con código*epsgCode* .

```csharp
public static Identifier Epsg(int epsgCode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| epsgCode | Int32 | codigo epsg |

### Valor_devuelto

Nuevo identificador con[`AuthorityName`](../authorityname) "EPSG" y[`AuthorityUniqueIdentifier`](../authorityuniqueidentifier)*epsgCode* . Si*epsgCode* es menor que 0 - retorno`null` ;

### Ver también

* class [Identifier](../../identifier)
* espacio de nombres [Aspose.Gis.SpatialReferencing](../../identifier)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
