---
title: IXPathResult
second_title: Referencia de API de Aspose.SVG para .NET
description: ElXPathResult La interfaz representa el resultado de la evaluación de una expresión XPath 1.0 dentro del contexto de un nodo en particular. Dado que la evaluación de una expresión XPath puede generar varios tipos de resultados este objeto hace posible descubrir y manipular el tipo y el valor del resultado.
type: docs
weight: 1350
url: /es/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

El`XPathResult` La interfaz representa el resultado de la evaluación de una expresión XPath 1.0 dentro del contexto de un nodo en particular. Dado que la evaluación de una expresión XPath puede generar varios tipos de resultados, este objeto hace posible descubrir y manipular el tipo y el valor del resultado.

```csharp
public interface IXPathResult
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue) { get; } | El valor de este resultado booleano. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate) { get; } | Significa que el iterador ha dejado de ser válido. cierto si`tipo de resultado` es`Iterador de nodo desordenado` tipo o`Iterador de nodo ordenado` tipo y el documento ha sido modificado desde que se devolvió este resultado. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue) { get; } | El valor de este resultado numérico. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype) { get; } | Un código que representa el tipo de este resultado, según lo define http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype) enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue) { get; } | El valor de este resultado de nodo único, que puede ser`nulo` . |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength) { get; } | El número de nodos en la instantánea de resultados. Los valores válidos para los índices snapshotItem son`0` a`snapshotLength-1` inclusive. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue) { get; } | El valor de esta cadena result. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext)() | itera y devuelve el siguiente nodo del conjunto de nodos o`nulo` si no hay más nodos. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem)(int) | Devuelve el`índice` º elemento en la colección de instantáneas. Si`índice`es mayor que o igual al número de nodos en la lista, este método devuelve`nulo` . A diferencia del resultado del iterador , la instantánea no se vuelve inválida, pero es posible que no se corresponda con el documento actual si está mutado. |

### Ver también

* espacio de nombres [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
