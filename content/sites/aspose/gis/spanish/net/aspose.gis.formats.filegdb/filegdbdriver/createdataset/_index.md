---
title: CreateDataset
second_title: Referencia de API de Aspose.GIS para .NET
description: Crea un conjunto de datos.
type: docs
weight: 50
url: /es/net/aspose.gis.formats.filegdb/filegdbdriver/createdataset/
---
## CreateDataset(string, FileGdbOptions) {#createdataset_5}

Crea un conjunto de datos.

```csharp
public Dataset CreateDataset(string path, FileGdbOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | Ruta al conjunto de datos. |
| options | FileGdbOptions | Opciones específicas del conductor. |

### Valor_devuelto

una instancia de[`Dataset`](../../../aspose.gis/dataset).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este controlador. |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../../aspose.gis/gisexception) | Error al leer el conjunto de datos. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir conjuntos de datos (ver[`CanOpenDatasets`](../../../aspose.gis/filedriver/canopendatasets)). |
| InvalidOperationException | El conjunto de datos ya existe. |

### Ver también

* class [Dataset](../../../aspose.gis/dataset)
* class [FileGdbOptions](../../filegdboptions)
* class [FileGdbDriver](../../filegdbdriver)
* espacio de nombres [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* asamblea [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath, DriverOptions) {#createdataset_1}

Crea un conjunto de datos.

```csharp
public override Dataset CreateDataset(AbstractPath path, DriverOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | AbstractPath | Ruta al conjunto de datos. |
| options | DriverOptions | Opciones específicas del conductor. |

### Valor_devuelto

una instancia de[`Dataset`](../../../aspose.gis/dataset).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este controlador. |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../../aspose.gis/gisexception) | Error al leer el conjunto de datos. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir conjuntos de datos (ver[`CanOpenDatasets`](../../../aspose.gis/filedriver/canopendatasets)). |
| InvalidOperationException | El conjunto de datos ya existe. |

### Ver también

* class [Dataset](../../../aspose.gis/dataset)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [DriverOptions](../../../aspose.gis/driveroptions)
* class [FileGdbDriver](../../filegdbdriver)
* espacio de nombres [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* asamblea [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath, FileGdbOptions) {#createdataset_2}

Crea un conjunto de datos.

```csharp
public Dataset CreateDataset(AbstractPath path, FileGdbOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | AbstractPath | Ruta al conjunto de datos. |
| options | FileGdbOptions | Opciones específicas del conductor. |

### Valor_devuelto

una instancia de[`Dataset`](../../../aspose.gis/dataset).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este controlador. |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../../aspose.gis/gisexception) | Error al leer el conjunto de datos. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir conjuntos de datos (ver[`CanOpenDatasets`](../../../aspose.gis/filedriver/canopendatasets)). |
| InvalidOperationException | El conjunto de datos ya existe. |

### Ver también

* class [Dataset](../../../aspose.gis/dataset)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [FileGdbOptions](../../filegdboptions)
* class [FileGdbDriver](../../filegdbdriver)
* espacio de nombres [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
