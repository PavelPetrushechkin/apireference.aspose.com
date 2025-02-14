---
title: XpsCanvas
second_title: Aspose.Page per riferimento all'API .NET
description: Caratteristiche dellelemento Canvas incapsulante della classe. Questo elemento raggruppa gli elementi insieme. Ad esempio gli elementi di Glifi e Percorso possono essere raggruppati in unarea di disegno per essere identificati come ununità come destinazione di un collegamento ipertestuale o per applicare un valore di proprietà composto a ciascun elemento figlio e antenato.
type: docs
weight: 2910
url: /it/net/aspose.page.xps.xpsmodel/xpscanvas/
---
## XpsCanvas class

Caratteristiche dell'elemento Canvas incapsulante della classe. Questo elemento raggruppa gli elementi insieme. Ad esempio, gli elementi di Glifi e Percorso possono essere raggruppati in un'area di disegno per essere identificati come un'unità (come destinazione di un collegamento ipertestuale) o per applicare un valore di proprietà composto a ciascun elemento figlio e antenato.

```csharp
public sealed class XpsCanvas : XpsContentElement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Clip](../../aspose.page.xps.xpsmodel/xpscontentelement/clip) { get; set; } | Restituisce/imposta l'istanza della geometria del percorso che limita la regione di rendering dell'elemento. |
| [Count](../../aspose.page.xps.xpsmodel/xpselement/count) { get; } | Restituisce il numero di elementi figlio. |
| [EdgeMode](../../aspose.page.xps.xpsmodel/xpscanvas/edgemode) { get; set; } | Restituisce/imposta il valore che controlla come vengono renderizzati i bordi dei percorsi all'interno dell'area di disegno. |
| [HyperlinkTarget](../../aspose.page.xps.xpsmodel/xpshyperlinkelement/hyperlinktarget) { get; set; } | Restituisce/imposta l'oggetto di destinazione del collegamento ipertestuale. |
| [Item](../../aspose.page.xps.xpsmodel/xpselement/item) { get; } | Fornisce l'accesso ai figli dell'elemento in base all'indice*i* . |
| [Opacity](../../aspose.page.xps.xpsmodel/xpscontentelement/opacity) { get; set; } | Restituisce/imposta il valore che definisce la trasparenza uniforme dell'elemento. |
| [OpacityMask](../../aspose.page.xps.xpsmodel/xpscontentelement/opacitymask) { get; set; } | Restituisce/imposta il pennello specificando una maschera di valori alfa che viene applicata all'elemento allo stesso modo dell'attributo Opacità, ma consentendo valori alfa diversi per aree diverse dell'elemento. |
| [RenderTransform](../../aspose.page.xps.xpsmodel/xpscontentelement/rendertransform) { get; set; } | Restituisce/imposta la matrice di trasformazione affine stabilendo un nuovo frame di coordinate per tutti gli attributi dell'elemento e per tutti gli elementi figlio (se presenti). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add&lt;T&gt;](../../aspose.page.xps.xpsmodel/xpscanvas/add)(T) | Aggiunge un elemento all'elenco figlio di questa tela. |
| [AddCanvas](../../aspose.page.xps.xpsmodel/xpscanvas/addcanvas)() | Aggiunge una nuova tela all'elenco figlio di questa tela. |
| [AddGlyphs](../../aspose.page.xps.xpsmodel/xpscanvas/addglyphs)(string, float, FontStyle, float, float, string) | Aggiunge nuovi glifi all'elenco figlio di questa tela. |
| [AddPath](../../aspose.page.xps.xpsmodel/xpscanvas/addpath)(XpsPathGeometry) | Aggiunge un nuovo percorso all'elenco figlio di questa tela. |
| [Clone](../../aspose.page.xps.xpsmodel/xpscanvas/clone)() | Clona questa tela. |
| [GetEnumerator](../../aspose.page.xps.xpsmodel/xpselement/getenumerator)() | Implementazione diIEnumerable interfaccia. |
| [Insert&lt;T&gt;](../../aspose.page.xps.xpsmodel/xpscanvas/insert)(int, T) | Inserisce un elemento nell'elenco figlio di questo canvas in*index* posizione. |
| [InsertCanvas](../../aspose.page.xps.xpsmodel/xpscanvas/insertcanvas)(int) | Inserisce una nuova tela nell'elenco figlio di questa tela in*index* posizione. |
| [InsertGlyphs](../../aspose.page.xps.xpsmodel/xpscanvas/insertglyphs)(int, string, float, FontStyle, float, float, string) | Inserisce nuovi glifi nell'elenco figlio di questa tela in*index* posizione. |
| [InsertPath](../../aspose.page.xps.xpsmodel/xpscanvas/insertpath)(int, XpsPathGeometry) | Inserisce un nuovo percorso nell'elenco figlio di questo canvas in*index* posizione. |

### Guarda anche

* class [XpsContentElement](../xpscontentelement)
* spazio dei nomi [Aspose.Page.XPS.XpsModel](../../aspose.page.xps.xpsmodel)
* assemblea [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
