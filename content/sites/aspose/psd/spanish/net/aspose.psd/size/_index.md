---
title: Size
second_title: Referencia de API de Aspose.PSD para .NET
description: Representa el tamaño.
type: docs
weight: 5480
url: /es/net/aspose.psd/size/
---
## Size structure

Representa el tamaño.

```csharp
public struct Size
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Size](size#constructor)(Point) | Inicializa una nueva instancia del[`Size`](../size) estructura de lo especificado[`Point`](../point) . |
| [Size](size#constructor_1)(int, int) | Inicializa una nueva instancia del[`Size`](../size) estructura de las dimensiones especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty) { get; } | Obtiene una nueva instancia del[`Size`](../size) estructura que tiene[`Width`](./width) y[`Height`](./height) valores establecidos en cero. |
| [Height](../../aspose.psd/size/height) { get; set; } | Obtiene o establece el componente vertical de este[`Size`](../size) . |
| [IsEmpty](../../aspose.psd/size/isempty) { get; } | Obtiene un valor que indica si este[`Size`](../size) tiene ancho y alto de 0. |
| [Width](../../aspose.psd/size/width) { get; set; } | Obtiene o establece el componente horizontal de este[`Size`](../size) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/size/add)(Size, Size) | Suma el ancho y alto de uno[`Size`](../size) estructura a la anchura y altura de otra[`Size`](../size)estructura. |
| static [Ceiling](../../aspose.psd/size/ceiling)(SizeF) | Convierte el especificado[`SizeF`](../sizef) estructura a un[`Size`](../size) estructura redondeando los valores de la[`Size`](../size) estructura a los siguientes valores enteros más altos. |
| static [Round](../../aspose.psd/size/round)(SizeF) | Convierte el especificado[`SizeF`](../sizef) estructura a un[`Size`](../size) estructura redondeando los valores de la[`SizeF`](../sizef) estructura a los valores enteros más cercanos. |
| static [Subtract](../../aspose.psd/size/subtract)(Size, Size) | Resta el ancho y el alto de uno[`Size`](../size) estructura de la anchura y la altura de otra[`Size`](../size)estructura. |
| static [Truncate](../../aspose.psd/size/truncate)(SizeF) | Convierte el especificado[`SizeF`](../sizef) estructura a un[`Size`](../size) estructura truncando los valores de la[`SizeF`](../sizef) estructura a los siguientes valores enteros más bajos. |
| override [Equals](../../aspose.psd/size/equals)(object) | Pruebas para ver si el objeto especificado es un[`Size`](../size) con las mismas dimensiones que este[`Size`](../size) . |
| override [GetHashCode](../../aspose.psd/size/gethashcode)() | Devuelve un código hash para este[`Size`](../size)estructura. |
| override [ToString](../../aspose.psd/size/tostring)() | Crea una cadena legible por humanos que representa este[`Size`](../size) . |
| [operator +](../../aspose.psd/size/op_addition) | Suma el ancho y alto de uno[`Size`](../size) estructura a la anchura y altura de otra[`Size`](../size)estructura. |
| [operator ==](../../aspose.psd/size/op_equality) | Comprueba si dos[`Size`](../size) las estructuras son iguales. |
| [explicit operator](../../aspose.psd/size/op_explicit) | Convierte el especificado[`Size`](../size) a un[`Point`](../point) . |
| [implicit operator](../../aspose.psd/size/op_implicit) | Convierte el especificado[`Size`](../size) a un[`SizeF`](../sizef) . |
| [operator !=](../../aspose.psd/size/op_inequality) | Comprueba si dos[`Size`](../size) las estructuras son diferentes. |
| [operator -](../../aspose.psd/size/op_subtraction) | Resta el ancho y el alto de uno[`Size`](../size) estructura de la anchura y la altura de otra[`Size`](../size)estructura. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
