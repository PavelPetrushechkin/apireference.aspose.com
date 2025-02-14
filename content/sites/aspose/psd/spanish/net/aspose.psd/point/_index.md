---
title: Point
second_title: Referencia de API de Aspose.PSD para .NET
description: Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.
type: docs
weight: 5190
url: /es/net/aspose.psd/point/
---
## Point structure

Representa un par ordenado de coordenadas x e y enteras que define un punto en un plano bidimensional.

```csharp
public struct Point
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Point](point#constructor_1)(int) | Inicializa una nueva instancia del[`Point`](../point)estructura usando coordenadas especificadas por un valor entero. |
| [Point](point#constructor)(Size) | Inicializa una nueva instancia del[`Point`](../point) estructura de la[`Size`](../size)estructura. |
| [Point](point#constructor_2)(int, int) | Inicializa una nueva instancia del[`Point`](../point) estructura con las coordenadas especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty) { get; } | Obtiene una nueva instancia del[`Point`](../point) estructura que tiene[`X`](./x) y[`Y`](./y) valores establecidos en cero. |
| [IsEmpty](../../aspose.psd/point/isempty) { get; } | Obtiene un valor que indica si este[`Point`](../point) está vacío. |
| [X](../../aspose.psd/point/x) { get; set; } | Obtiene o establece la coordenada x de este[`Point`](../point) . |
| [Y](../../aspose.psd/point/y) { get; set; } | Obtiene o establece la coordenada y de este[`Point`](../point) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Add](../../aspose.psd/point/add)(Point, Size) | Agrega el especificado[`Size`](../size) a lo especificado[`Point`](../point) . |
| static [Ceiling](../../aspose.psd/point/ceiling)(PointF) | Convierte el especificado[`PointF`](../pointf) a un[`Point`](../point) redondeando los valores de[`PointF`](../pointf) a los siguientes valores enteros más altos. |
| static [Round](../../aspose.psd/point/round)(PointF) | Convierte el especificado[`PointF`](../pointf) a un[`Point`](../point) objeto redondeando el[`Point`](../point) valores al entero más próximo. |
| static [Subtract](../../aspose.psd/point/subtract)(Point, Size) | Devuelve el resultado de restar especificado[`Size`](../size) de lo especificado[`Point`](../point) . |
| static [Truncate](../../aspose.psd/point/truncate)(PointF) | Convierte el especificado[`PointF`](../pointf) a un[`Point`](../point) truncando los valores de[`Point`](../point) . |
| override [Equals](../../aspose.psd/point/equals)(object) | Especifica si este[`Point`](../point)contiene las mismas coordenadas que el especificadoObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode)() | Devuelve un código hash para este[`Point`](../point) . |
| [Offset](../../aspose.psd/point/offset#offset)(Point) | Traduce esto[`Point`](../point) por el especificado[`Point`](../point) . |
| [Offset](../../aspose.psd/point/offset#offset_1)(int, int) | Traduce esto[`Point`](../point) por la cantidad especificada. |
| override [ToString](../../aspose.psd/point/tostring)() | Convierte esto[`Point`](../point) a una cadena legible por humanos. |
| [operator +](../../aspose.psd/point/op_addition) | Traduce un[`Point`](../point) por un dado[`Size`](../size) . |
| [operator ==](../../aspose.psd/point/op_equality) | Compara dos[`Point`](../point) objetos. El resultado especifica si los valores de la[`X`](./x) y[`Y`](./y) propiedades de los dos[`Point`](../point) los objetos son iguales. |
| [explicit operator](../../aspose.psd/point/op_explicit) | Convierte el especificado[`Point`](../point) estructura a un[`Size`](../size)estructura. |
| [implicit operator](../../aspose.psd/point/op_implicit) | Convierte el especificado[`Point`](../point) estructura a la[`PointF`](../pointf)estructura. |
| [operator !=](../../aspose.psd/point/op_inequality) | Compara dos[`Point`](../point) objetos. El resultado especifica si los valores de la[`X`](./x) o[`Y`](./y) propiedades de los dos[`Point`](../point) los objetos son desiguales. |
| [operator -](../../aspose.psd/point/op_subtraction) | Traduce un[`Point`](../point)por el negativo de un dado[`Size`](../size) . |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
