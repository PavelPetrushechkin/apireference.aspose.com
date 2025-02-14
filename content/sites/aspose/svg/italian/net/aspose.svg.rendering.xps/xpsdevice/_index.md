---
title: XpsDevice
second_title: Riferimento API Aspose.SVG per .NET
description: Rappresenta il rendering in un documento xps.
type: docs
weight: 3000
url: /it/net/aspose.svg.rendering.xps/xpsdevice/
---
## XpsDevice class

Rappresenta il rendering in un documento xps.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe. |
| [XpsDevice](xpsdevice#constructor_4)(Stream) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe. |
| [XpsDevice](xpsdevice#constructor_5)(string) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe. |
| [XpsDevice](xpsdevice#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe per opzioni di rendering e provider di streaming. |
| [XpsDevice](xpsdevice#constructor_2)(XpsRenderingOptions, Stream) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe per opzioni di rendering e flusso di output. |
| [XpsDevice](xpsdevice#constructor_3)(XpsRenderingOptions, string) | Inizializza una nuova istanza di[`XpsDevice`](../xpsdevice) classe per opzioni di rendering e nome del file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.svg.rendering/device`2/options) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddRect](../../aspose.svg.rendering.xps/xpsdevice/addrect)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| override [BeginDocument](../../aspose.svg.rendering.xps/xpsdevice/begindocument)(Document) | Inizia il rendering del documento. |
| override [BeginElement](../../aspose.svg.rendering.xps/xpsdevice/beginelement)(Element, RectangleF) | Inizia il rendering dell'elemento. |
| override [BeginPage](../../aspose.svg.rendering.xps/xpsdevice/beginpage)(SizeF) | Inizia il rendering della nuova pagina. |
| override [Clip](../../aspose.svg.rendering.xps/xpsdevice/clip)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare la regione da riempire. Questo metodo termina il percorso corrente. |
| override [ClosePath](../../aspose.svg.rendering.xps/xpsdevice/closepath)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non esegue alcuna operazione. Questo operatore termina il sottopercorso corrente. Aggiungendo un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia all'endpoint raggiunto dal metodo "ClosePath". |
| override [CubicBezierTo](../../aspose.svg.rendering.xps/xpsdevice/cubicbezierto)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt2, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [Dispose](../../aspose.svg.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.svg.rendering.xps/xpsdevice/drawimage)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| virtual [EndDocument](../../aspose.svg.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.svg.rendering.xps/xpsdevice/endelement)(Element) | Termina il rendering dell'elemento. |
| override [EndPage](../../aspose.svg.rendering.xps/xpsdevice/endpage)() | Termina il rendering della pagina corrente. |
| override [Fill](../../aspose.svg.rendering.xps/xpsdevice/fill)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da più sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| override [FillText](../../aspose.svg.rendering.xps/xpsdevice/filltext)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| override [Flush](../../aspose.svg.rendering.xps/xpsdevice/flush)() | Scarica tutti i dati nel flusso di output. |
| override [LineTo](../../aspose.svg.rendering.xps/xpsdevice/lineto)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| override [MoveTo](../../aspose.svg.rendering.xps/xpsdevice/moveto)(PointF) | Inizia un nuovo sottopercorso spostando il punto corrente sulle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il metodo di costruzione del percorso precedente nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "MoveTo" rimane nel percorso. |
| override [RestoreGraphicContext](../../aspose.svg.rendering.xps/xpsdevice/restoregraphiccontext)() | Ripristina l'intero contesto grafico al valore precedente espellendolo dallo stack. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device`2/savegraphiccontext)() |  |
| override [Stroke](../../aspose.svg.rendering.xps/xpsdevice/stroke)() | Traccia una linea lungo il percorso corrente. La linea tratteggiata segue ogni segmento diritto o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascuno dei sottopercorsi del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| override [StrokeAndFill](../../aspose.svg.rendering.xps/xpsdevice/strokeandfill)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| override [StrokeText](../../aspose.svg.rendering.xps/xpsdevice/stroketext)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext) | Contiene i parametri di controllo della grafica correnti per XpsDevice. Questi parametri definiscono la struttura globale all'interno della quale vengono eseguiti gli operatori grafici. |

### Guarda anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.svg.rendering/device-2)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext)
* class [XpsRenderingOptions](../xpsrenderingoptions)
* spazio dei nomi [Aspose.Svg.Rendering.Xps](../../aspose.svg.rendering.xps)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
