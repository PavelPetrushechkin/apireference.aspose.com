---
title: Render
second_title: Riferimento API Aspose.SVG per .NET
description: Definisce il metodo per il rendering multiploSVGDocumentaspose.svg/svgdocument s nello specificoIDeviceaspose.svg.rendering/idevice . Il rendering verrà eseguito quando non ci sono operazioni di rete per il caricamento di risorse timer attivi attività di animazione o quando è trascorso il timeout specificato.
type: docs
weight: 20
url: /it/net/aspose.svg.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Definisce il metodo per il rendering multiplo[`SVGDocument`](../../../aspose.svg/svgdocument) s nello specifico[`IDevice`](../../idevice) . Il rendering verrà eseguito quando non ci sono operazioni di rete per il caricamento di risorse, timer attivi, attività di animazione o quando è trascorso il timeout specificato.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| device | IDevice | Il dispositivo di uscita. |
| timeout | TimeSpan | UNTimeSpan che rappresenta il numero di millisecondi di attesa, oppure aTimeSpan che rappresenta -1 millisecondo di attesa indefinitamente. |
| documents | SVGDocument[] | I documenti da rendere. |

### Guarda anche

* interface [IDevice](../../idevice)
* class [SVGDocument](../../../aspose.svg/svgdocument)
* class [SvgRenderer](../../svgrenderer)
* spazio dei nomi [Aspose.Svg.Rendering](../../svgrenderer)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
