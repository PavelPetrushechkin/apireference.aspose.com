---
title: RemoveEventListener
second_title: Aspose.SVG für .NET-API-Referenz
description: Diese Methode ermöglicht das Entfernen von EreignisListenern aus dem Ereignisziel. Wenn anIEventListeneraspose.svg.dom.events/ieventlistener wird aus einem entferntEventTargetaspose.svg.dom/eventtarget während es ein Ereignis verarbeitet wird es nicht durch die aktuellen Aktionen ausgelöst. EreignisListener können nie aufgerufen werden nachdem sie entfernt wurden.
type: docs
weight: 40
url: /de/net/aspose.svg.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |
| handler | DOMEventHandler | Das[`DOMEventHandler`](../../../aspose.svg.dom.events/domeventhandler) Parameter gibt die an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als erfassender Listener registriert wurde oder nicht. Wenn ein Listener zweimal registriert wurde, einer mit Erfassung und einer ohne, muss jeder separat entfernt werden. Das Entfernen eines erfassenden Listeners wirkt sich nicht auf eine nicht erfassende Version aus desselben Zuhörers und umgekehrt. |

### Siehe auch

* delegate [DOMEventHandler](../../../aspose.svg.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* namensraum [Aspose.Svg.Dom](../../eventtarget)
* Montage [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |
| listener | IEventListener | Das[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) Parameter gibt die an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namensraum [Aspose.Svg.Dom](../../eventtarget)
* Montage [Aspose.SVG](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |
| listener | IEventListener | Das[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) Parameter gibt die an[`IEventListener`](../../../aspose.svg.dom.events/ieventlistener) entfernt werden. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als erfassender Listener registriert wurde oder nicht. Wenn ein Listener zweimal registriert wurde, einer mit Erfassung und einer ohne, muss jeder separat entfernt werden. Das Entfernen eines erfassenden Listeners wirkt sich nicht auf eine nicht erfassende Version aus desselben Zuhörers und umgekehrt. |

### Siehe auch

* interface [IEventListener](../../../aspose.svg.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namensraum [Aspose.Svg.Dom](../../eventtarget)
* Montage [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
