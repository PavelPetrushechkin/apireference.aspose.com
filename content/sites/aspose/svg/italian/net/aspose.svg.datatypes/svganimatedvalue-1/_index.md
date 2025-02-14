---
title: SVGAnimatedValueT
second_title: Riferimento API Aspose.SVG per .NET
description: Utilizzato per gli attributi dei tipi che possono essere animati.
type: docs
weight: 210
url: /it/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue&lt;T&gt; class

Utilizzato per gli attributi dei tipi che possono essere animati.

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| Parametro | Descrizione |
| --- | --- |
| T | L'oggetto Valore SVG. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue`1/animval) { get; } | Se l'attributo o la proprietà specificati è in fase di animazione, contiene il valore animato corrente dell'attributo o della proprietà. Se l'attributo o la proprietà specificati non è attualmente animato, contiene lo stesso valore di baseVal. |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue`1/baseval) { get; set; } | Il valore di base dell'attributo specificato prima di applicare qualsiasi animazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Rilascia risorse non gestite e, facoltativamente, gestite. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |

### Guarda anche

* class [SVGValueType](../svgvaluetype)
* spazio dei nomi [Aspose.Svg.DataTypes](../../aspose.svg.datatypes)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
