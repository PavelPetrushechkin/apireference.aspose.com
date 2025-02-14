---
title: CreatePathFigure
second_title: Aspose.Page per riferimento all'API .NET
description: Crea una nuova figura di percorso.
type: docs
weight: 280
url: /it/net/aspose.page.xps/xpsdocument/createpathfigure/
---
## CreatePathFigure(PointF, bool) {#createpathfigure}

Crea una nuova figura di percorso.

```csharp
public XpsPathFigure CreatePathFigure(PointF startPoint, bool isClosed = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPoint | PointF | Il punto di partenza per il primo segmento della figura del percorso. |
| isClosed | Boolean | Specifica se il percorso è chiuso. Se impostato su true, il tratto viene disegnato "chiuso", ovvero l'ultimo punto nell'ultimo segmento della figura del percorso è collegato a il punto specificato nell'attributo StartPoint, altrimenti il tratto viene tracciato "aperto" e l'ultimo punto non è collegato al punto iniziale. Applicabile solo se la figura del percorso è utilizzata in un elemento {Percorso} che specifica un tratto. |

### Valore di ritorno

Nuova figura del percorso.

### Guarda anche

* class [XpsPathFigure](../../../aspose.page.xps.xpsmodel/xpspathfigure)
* class [XpsDocument](../../xpsdocument)
* spazio dei nomi [Aspose.Page.XPS](../../xpsdocument)
* assemblea [Aspose.Page](../../../)

---

## CreatePathFigure(PointF, List&lt;XpsPathSegment&gt;, bool) {#createpathfigure_1}

Crea una nuova figura di percorso.

```csharp
public XpsPathFigure CreatePathFigure(PointF startPoint, List<XpsPathSegment> segments, 
    bool isClosed = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPoint | PointF | Il punto di partenza per il primo segmento della figura del percorso. |
| segments | List`1 | Elenco dei segmenti di percorso. |
| isClosed | Boolean | Specifica se il percorso è chiuso. Se impostato su true, il tratto viene disegnato "chiuso", ovvero l'ultimo punto nell'ultimo segmento della figura del percorso è collegato a il punto specificato nell'attributo StartPoint, altrimenti il tratto viene tracciato "aperto" e l'ultimo punto non è collegato al punto iniziale. Applicabile solo se la figura del percorso è utilizzata in un elemento {Percorso} che specifica un tratto. |

### Valore di ritorno

Nuova figura del percorso.

### Guarda anche

* class [XpsPathFigure](../../../aspose.page.xps.xpsmodel/xpspathfigure)
* class [XpsPathSegment](../../../aspose.page.xps.xpsmodel/xpspathsegment)
* class [XpsDocument](../../xpsdocument)
* spazio dei nomi [Aspose.Page.XPS](../../xpsdocument)
* assemblea [Aspose.Page](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
