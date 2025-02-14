---
title: LayeredSymbolizer
second_title: Riferimento API Aspose.GIS per .NET
description: Un simbolizzatore che rende molti altri simbolizzatori.
type: docs
weight: 1730
url: /it/net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---
## LayeredSymbolizer class

Un simbolizzatore che rende molti altri simbolizzatori.

```csharp
public class LayeredSymbolizer : VectorSymbolizer, IReadOnlyList<VectorSymbolizer>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayeredSymbolizer](layeredsymbolizer#constructor)() | Crea una nuova istanza. |
| [LayeredSymbolizer](layeredsymbolizer#constructor_1)(RenderingOrder) | Crea una nuova istanza. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/count) { get; } | Ottiene il numero di simbolizzatori. |
| [Item](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/item) { get; } | Ottiene il simbolizzatore in corrispondenza dell'indice specificato. |
| [RenderingOrder](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/renderingorder) { get; set; } | Determina l'ordine di rendering. ByFeatures - esegue il rendering di tutti i simbolizzatori per l'elemento, quindi passa all'elemento successivo.ByLayers - esegue il rendering di tutte le caratteristiche con il simbolizzatore, quindi passa al simbolizzatore successivo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/add)(VectorSymbolizer) | Aggiunge il simbolizzatore specificato. |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |

### Guarda anche

* class [VectorSymbolizer](../vectorsymbolizer)
* spazio dei nomi [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers)
* assemblea [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
