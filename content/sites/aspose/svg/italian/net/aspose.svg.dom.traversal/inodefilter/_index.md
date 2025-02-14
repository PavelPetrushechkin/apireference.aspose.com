---
title: INodeFilter
second_title: Riferimento API Aspose.SVG per .NET
description: I filtri sono oggetti che sanno come filtrare i nodi. Se a un NodeIterator o TreeWalker viene assegnato un NodeFilter applica il filtro prima di restituire il successivo nodo . Se il filtro dice di accettare il nodo la logica di attraversamento lo restituisce  in caso contrario traversal cerca il nodo successivo e fa finta che il nodo rifiutato non fosse presente.
type: docs
weight: 1240
url: /it/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

I filtri sono oggetti che sanno come "filtrare" i nodi. Se a un NodeIterator o TreeWalker viene assegnato un NodeFilter, applica il filtro prima di restituire il successivo nodo . Se il filtro dice di accettare il nodo, la logica di attraversamento lo restituisce ; in caso contrario, traversal cerca il nodo successivo e fa finta che il nodo rifiutato non fosse presente.

Il DOM non fornisce alcun filtro. NodeFilter è solo un'interfaccia che gli utenti possono implementare per fornire i propri filtri.

I NodeFilter non hanno bisogno di sapere come passare da un nodo a un nodo, né hanno bisogno di sapere nulla sulla struttura dati che sta attraversando. Questo rende molto facile scrivere filtri, poiché l'unica cosa che devono sapere come fare è valutare un singolo nodo. Un filtro può essere utilizzato con diversi tipi di attraversamenti, incoraggiando il riutilizzo del codice.

Vedi anche il[Document Object Model (DOM) Livello 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @dal livello DOM 2

```csharp
public interface INodeFilter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode)(Node) | Verifica se un nodo specificato è visibile nella vista logica di un TreeWalker o NodeIterator . Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; normalmente non viene chiamato direttamente dal codice utente . (Anche se potresti farlo se volessi utilizzare lo stesso filtro per guidare la tua logica dell'applicazione.) |

### Guarda anche

* spazio dei nomi [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
