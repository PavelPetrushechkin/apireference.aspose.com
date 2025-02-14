---
title: OpenLayer
second_title: Referencia de API de Aspose.GIS para .NET
description: Abre la capa con el nombre especificado para lectura.
type: docs
weight: 110
url: /es/net/aspose.gis/dataset/openlayer/
---
## Dataset.OpenLayer method

Abre la capa con el nombre especificado para lectura.

```csharp
public abstract VectorLayer OpenLayer(string name, DriverOptions options = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| name | String | Nombre de la capa a abrir. |
| options | DriverOptions | Opciones abiertas. |

### Valor_devuelto

La capa se abrió para lectura.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La capa con el nombre especificado no existe; El objeto de opciones tiene un tipo incorrecto para este conjunto de datos. |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este conjunto de datos. |
| ArgumentNullException | El nombre es`null`. |
| [GisException](../../gisexception) | Error al leer la entidad de la capa. |
| IOException | Se produjo un error de E/S. |

### Ver también

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [Dataset](../../dataset)
* espacio de nombres [Aspose.Gis](../../dataset)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
