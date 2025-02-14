---
title: DispatchEvent
second_title: Aspose.SVG für .NET-API-Referenz
description: Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung.
type: docs
weight: 20
url: /de/net/aspose.svg.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | Event | Gibt den Ereignistyp, das Verhalten und die Kontextinformationen an, die bei der Verarbeitung des Ereignisses verwendet werden sollen. |

### Rückgabewert

Der Rückgabewert von[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent) gibt an, ob einer der Listener, die das Ereignis behandelt haben, aufgerufen hat[`PreventDefault`](../../event/preventdefault) . Wenn[`PreventDefault`](../../event/preventdefault) aufgerufen wurde, ist der Wert falsch, sonst ist der Wert wahr.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) |  |

### Bemerkungen

Auf diese Weise gesendete Ereignisse haben das gleiche Erfassungs- und Bubbling-Verhalten wie direkt von der Implementierung gesendete Ereignisse. Das Ziel des Ereignisses ist die[`EventTarget`](../../../aspose.svg.dom/eventtarget) auf welche[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent) heißt.

### Siehe auch

* class [Event](../../event)
* interface [IEventTarget](../../ieventtarget)
* namensraum [Aspose.Svg.Dom.Events](../../ieventtarget)
* Montage [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
