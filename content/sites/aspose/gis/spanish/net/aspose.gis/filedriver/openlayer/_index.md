---
title: OpenLayer
second_title: Referencia de API de Aspose.GIS para .NET
description: Abre la capa para lectura.
type: docs
weight: 90
url: /es/net/aspose.gis/filedriver/openlayer/
---
## OpenLayer(string) {#openlayer_2}

Abre la capa para lectura.

```csharp
public VectorLayer OpenLayer(string path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | Ruta al archivo. |

### Valor_devuelto

una instancia de[`VectorLayer`](../../vectorlayer).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../gisexception) | Error al leer la característica del archivo. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir capas vectoriales (ver[`CanOpenLayers`](../canopenlayers)). |

### Ver también

* class [VectorLayer](../../vectorlayer)
* class [FileDriver](../../filedriver)
* espacio de nombres [Aspose.Gis](../../filedriver)
* asamblea [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath) {#openlayer}

Abre la capa para lectura.

```csharp
public VectorLayer OpenLayer(AbstractPath path)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | AbstractPath | Ruta al archivo. |

### Valor_devuelto

una instancia de[`VectorLayer`](../../vectorlayer).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../gisexception) | Error al leer la característica del archivo. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir capas vectoriales (ver[`CanOpenLayers`](../canopenlayers)). |

### Ver también

* class [VectorLayer](../../vectorlayer)
* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* espacio de nombres [Aspose.Gis](../../filedriver)
* asamblea [Aspose.GIS](../../../)

---

## OpenLayer(string, DriverOptions) {#openlayer_3}

Abre la capa para lectura.

```csharp
public VectorLayer OpenLayer(string path, DriverOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | String | Ruta al archivo. |
| options | DriverOptions | Opciones específicas del conductor. |

### Valor_devuelto

una instancia de[`VectorLayer`](../../vectorlayer).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este controlador. |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../gisexception) | Error al leer la característica del archivo. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir capas vectoriales (ver[`CanOpenLayers`](../canopenlayers)). |

### Ver también

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [FileDriver](../../filedriver)
* espacio de nombres [Aspose.Gis](../../filedriver)
* asamblea [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, DriverOptions) {#openlayer_1}

Abre la capa para lectura.

```csharp
public abstract VectorLayer OpenLayer(AbstractPath path, DriverOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| path | AbstractPath | Ruta al archivo. |
| options | DriverOptions | Opciones específicas del conductor. |

### Valor_devuelto

una instancia de[`VectorLayer`](../../vectorlayer).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El objeto de opciones tiene un tipo incorrecto para este controlador. |
| ArgumentNullException | el camino es`null`. |
| [GisException](../../gisexception) | Error al leer la característica del archivo. |
| IOException | Se produjo un error de E/S. |
| NotSupportedException | El controlador no puede abrir capas vectoriales (ver[`CanOpenLayers`](../canopenlayers)). |

### Ver también

* class [VectorLayer](../../vectorlayer)
* class [AbstractPath](../../abstractpath)
* class [DriverOptions](../../driveroptions)
* class [FileDriver](../../filedriver)
* espacio de nombres [Aspose.Gis](../../filedriver)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
