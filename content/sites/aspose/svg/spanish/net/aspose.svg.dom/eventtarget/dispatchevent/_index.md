---
title: DispatchEvent
second_title: Referencia de API de Aspose.SVG para .NET
description: Este método permite el envío de eventos al modelo de eventos de implementaciones.
type: docs
weight: 20
url: /es/net/aspose.svg.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Este método permite el envío de eventos al modelo de eventos de implementaciones.

```csharp
public bool DispatchEvent(Event @event)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| event | Event | Especifica el tipo de evento, el comportamiento y la información contextual que se utilizará para procesar el evento. |

### Valor_devuelto

El valor de retorno de`DispatchEvent` indica si alguno de los oyentes que manejaron el evento llamado[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault) . Si[`PreventDefault`](../../../aspose.svg.dom.events/event/preventdefault) fue llamado el valor es falso, de lo contrario el valor es verdadero.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../domexception) |  |

### Observaciones

Los eventos enviados de esta manera tendrán el mismo comportamiento de captura y burbujeo que los eventos enviados directamente por la implementación. El destino del evento es el[`EventTarget`](../../eventtarget) en la que`DispatchEvent` se llama.

### Ver también

* class [Event](../../../aspose.svg.dom.events/event)
* class [EventTarget](../../eventtarget)
* espacio de nombres [Aspose.Svg.Dom](../../eventtarget)
* asamblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
