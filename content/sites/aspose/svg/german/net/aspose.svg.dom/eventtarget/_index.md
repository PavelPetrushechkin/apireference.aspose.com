---
title: EventTarget
second_title: Aspose.SVG für .NET-API-Referenz
description: DieEventTarget./eventtarget Schnittstelle wird von allen Knoten in einer Implementierung implementiert die das DOMEreignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer CastingMethoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von EreignisListenern einEventTarget./eventtarget und Versand von Ereignissen dazuIEventTarget../aspose.svg.dom.events/ieventtarget .
type: docs
weight: 870
url: /de/net/aspose.svg.dom/eventtarget/
---
## EventTarget class

Die[`EventTarget`](../eventtarget) -Schnittstelle wird von allen Knoten in einer Implementierung implementiert, die das DOM-Ereignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer Casting-Methoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Ereignis-Listenern ein[`EventTarget`](../eventtarget) und Versand von Ereignissen dazu[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener#addeventlistener_1)(string, IEventListener) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener#addeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener#addeventlistener_2)(string, IEventListener, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener#removeeventlistener_1)(string, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener#removeeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener#removeeventlistener_2)(string, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |

### Siehe auch

* class [DOMObject](../domobject)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget)
* namensraum [Aspose.Svg.Dom](../../aspose.svg.dom)
* Montage [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
