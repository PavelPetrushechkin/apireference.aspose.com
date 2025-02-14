---
title: EditLayer
second_title: Riferimento API Aspose.GIS per .NET
description: Apre il livello con il nome specificato per la modifica.
type: docs
weight: 90
url: /it/net/aspose.gis/dataset/editlayer/
---
## Dataset.EditLayer method

Apre il livello con il nome specificato per la modifica.

```csharp
public abstract VectorLayer EditLayer(string name, DriverOptions options = null, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome del livello da modificare. |
| options | DriverOptions | Opzioni aperte. |
| spatialReferenceSystem | SpatialReferenceSystem | Sistema di riferimento spaziale per nuove geometrie. |

### Valore di ritorno

Il livello aperto per la modifica.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Il livello con il nome specificato non esiste; L'oggetto Opzioni ha un tipo errato per questo set di dati. |
| ArgumentException | L'oggetto Opzioni ha un tipo errato per questo set di dati. |
| ArgumentNullException | Il nome è`null`. |
| [GisException](../../gisexception) | Errore durante la lettura della funzione dal livello. |
| IOException | Si è verificato un errore di I/O. |

### Guarda anche

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [Dataset](../../dataset)
* spazio dei nomi [Aspose.Gis](../../dataset)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
