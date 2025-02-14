---
title: CreateExpression
second_title: Riferimento API Aspose.SVG per .NET
description: Crea unespressione XPath analizzata con spazi dei nomi risolti. Ciò è utile quando unespressione verrà riutilizzata in unapplicazione poiché consente di compilare la stringa dellespressione in una forma interna più efficiente e prerisolvere tutti i prefissi dello spazio dei nomi che si verificano allinterno dellespressione.
type: docs
weight: 10
url: /it/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crea un'espressione XPath analizzata con spazi dei nomi risolti. Ciò è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la stringa dell'espressione in una forma interna più efficiente e prerisolvere tutti i prefissi dello spazio dei nomi che si verificano all'interno dell'espressione.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expression | String | La stringa dell'espressione XPath da analizzare. |
| resolver | IXPathNSResolver | Il`risolutore` consente la traduzione di tutti i prefissi, incluso il`xml` prefisso dello spazio dei nomi, all'interno dell'espressione XPath negli URI dello spazio dei nomi appropriato . Se questo è specificato come`nullo` , qualsiasi prefisso dello spazio dei nomi all'interno dell'espressione risulterà[`DOMException`](../../../aspose.svg.dom/domexception) essendo generato con il codice`NAMESPACE_ERR`. |

### Valore di ritorno

Il modulo compilato dell'espressione XPath.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | INVALID_EXPRESSION_ERR: sollevato se l'espressione non è legale secondo le regole del[`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.svg.dom/domexception) | NAMESPACE_ERR: generato se l'espressione contiene i prefissi dello spazio dei nomi che non possono essere risolti dal[`IXPathNSResolver`](../../ixpathnsresolver). |

### Guarda anche

* interface [IXPathExpression](../../ixpathexpression)
* interface [IXPathNSResolver](../../ixpathnsresolver)
* interface [IXPathEvaluator](../../ixpathevaluator)
* spazio dei nomi [Aspose.Svg.Dom.XPath](../../ixpathevaluator)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
