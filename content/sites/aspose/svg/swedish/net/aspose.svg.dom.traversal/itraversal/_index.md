---
title: ITraversal
second_title: Aspose.SVG för .NET API Referens
description: Iteratorer används för att stega igenom en uppsättning noder t.ex. uppsättningen av noder i en NodeList dokumentunderträdet som styrs av en viss Nod resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIteratorimplementering för dokumentorder genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator.
type: docs
weight: 1260
url: /sv/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

Iteratorer används för att stega igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentunderträdet som styrs av en viss Nod, resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av -implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementering för dokument-order genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface ITraversal : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter) { get; } | Nodfiltret som används för att screena noder. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root) { get; } | Rotnoden för NodeIterator, som specificerades när it skapades. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow) { get; } | Det här attributet bestämmer vilka nodtyper som presenteras via iteratorn . Den tillgängliga uppsättningen konstanter definieras i gränssnittet NodeFilter. Noder som inte accepteras av whatToShow kommer att hoppas över, men deras barn kan fortfarande övervägas. Observera att detta överhopp har företräde framför filtret, om något. |

### Se även

* namnutrymme [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal)
* hopsättning [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
