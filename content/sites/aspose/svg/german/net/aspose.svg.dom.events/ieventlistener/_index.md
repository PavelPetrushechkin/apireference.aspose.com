---
title: IEventListener
second_title: Aspose.SVG für .NET-API-Referenz
description: DieIEventListener./ieventlistenerSchnittstelle ist die primäre Methode zur Behandlung von Ereignissen. Benutzer implementieren dieIEventListener./ieventlistener Schnittstelle und registrieren Sie ihren Listener auf einerEventTarget../aspose.svg.dom/eventtarget Verwendung derAddEventListener../aspose.svg.dom/eventtarget/addeventlistener method. Die Benutzer sollten auch ihre entfernenIEventListener./ieventlistener von seinemEventTarget../aspose.svg.dom/eventtarget nachdem sie die Verwendung des Listeners abgeschlossen haben.
type: docs
weight: 950
url: /de/net/aspose.svg.dom.events/ieventlistener/
---
## IEventListener interface

Die[`IEventListener`](../ieventlistener)Schnittstelle ist die primäre Methode zur Behandlung von Ereignissen. Benutzer implementieren die[`IEventListener`](../ieventlistener) Schnittstelle und registrieren Sie ihren Listener auf einer[`EventTarget`](../../aspose.svg.dom/eventtarget) Verwendung der[`AddEventListener`](../../aspose.svg.dom/eventtarget/addeventlistener) method. Die Benutzer sollten auch ihre entfernen[`IEventListener`](../ieventlistener) von seinem[`EventTarget`](../../aspose.svg.dom/eventtarget) nachdem sie die Verwendung des Listeners abgeschlossen haben.

```csharp
public interface IEventListener
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [HandleEvent](../../aspose.svg.dom.events/ieventlistener/handleevent)(Event) | Diese Methode wird immer dann aufgerufen, wenn ein Ereignis des Typs auftritt, für den die[`IEventListener`](../ieventlistener) Schnittstelle wurde registriert. |

### Bemerkungen

Wenn ein Knoten mit der cloneNode-Methode kopiert wird, werden die an den Quellknoten angehängten Ereignis-Listener nicht an den kopierten Knoten angehängt. Wenn der Benutzer möchte, dass dieselben Ereignis-Listener zu der neu erstellten Kopie hinzugefügt werden, muss der Benutzer sie manuell hinzufügen.

### Siehe auch

* namensraum [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* Montage [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
