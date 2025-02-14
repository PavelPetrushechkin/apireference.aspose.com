---
title: AsImage
second_title: Riferimento API Aspose.GIS per .NET
description: Esporta questa geometria in una rappresentazione dellimmagine.
type: docs
weight: 120
url: /it/net/aspose.gis.geometries/geometry/asimage/
---
## AsImage(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_1}

Esporta questa geometria in una rappresentazione dell'immagine.

```csharp
public void AsImage(AbstractPath outputPath, Measurement width, Measurement height, 
    Renderer renderer, VectorSymbolizer symbolizer = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputPath | AbstractPath | Percorso dell'immagine di output. |
| width | Measurement | Larghezza della mappa. |
| height | Measurement | Altezza della mappa. |
| renderer | Renderer | Rendering da usare. |
| symbolizer | VectorSymbolizer | Un simbolizzatore da utilizzare per il rendering. Se`null`, viene utilizzato il simbolizzatore predefinito. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Qualsiasi argomento`null`. |
| IOException | Si è verificato un errore di I/O. |
| [GisException](../../../aspose.gis/gisexception) | Errore durante l'elaborazione o la lettura dei dati GIS. |
| ArgumentException | L'unità di larghezza o altezza è!:Unit.MapUnits . |
| ArgumentOutOfRangeException | Larghezza o altezza è negativa o zero. |

### Guarda anche

* class [AbstractPath](../../../aspose.gis/abstractpath)
* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

---

## AsImage(string, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_2}

Esporta questa geometria in una rappresentazione dell'immagine.

```csharp
public void AsImage(string outputPath, Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputPath | String | Percorso dell'immagine di output. |
| width | Measurement | Larghezza della mappa. |
| height | Measurement | Altezza della mappa. |
| renderer | Renderer | Rendering da usare. |
| symbolizer | VectorSymbolizer | Un simbolizzatore da utilizzare per il rendering. Se`null`, viene utilizzato il simbolizzatore predefinito. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Qualsiasi argomento`null`. |
| IOException | Si è verificato un errore di I/O. |
| [GisException](../../../aspose.gis/gisexception) | Errore durante l'elaborazione o la lettura dei dati GIS. |
| ArgumentException | L'unità di larghezza o altezza è!:Unit.MapUnits . |
| ArgumentOutOfRangeException | Larghezza o altezza è negativa o zero. |

### Guarda anche

* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

---

## AsImage(Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage}

Esporta questa geometria in una rappresentazione dell'immagine.

```csharp
public Stream AsImage(Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | Measurement | Larghezza della mappa. |
| height | Measurement | Altezza della mappa. |
| renderer | Renderer | Rendering da usare. |
| symbolizer | VectorSymbolizer | Un simbolizzatore da utilizzare per il rendering. Se`null`, viene utilizzato il simbolizzatore predefinito. |

### Valore di ritorno

L'immagine come flusso

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Qualsiasi argomento`null`. |
| IOException | Si è verificato un errore di I/O. |
| [GisException](../../../aspose.gis/gisexception) | Errore durante l'elaborazione o la lettura dei dati GIS. |
| ArgumentException | L'unità di larghezza o altezza è!:Unit.MapUnits . |
| ArgumentOutOfRangeException | Larghezza o altezza è negativa o zero. |

### Guarda anche

* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
