---
title: SVGPoint
second_title: Referencia de API de Aspose.SVG para .NET
description: Muchas de las interfaces SVG DOM se refieren a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas x y. Cuando se usa en operaciones matriciales un SVGPoint se trata como un vector de la forma x y 1 Si un objeto SVGRect se designa como de solo lectura intentar asignarlo a uno de sus atributos resultar en una excepción lanzada.
type: docs
weight: 270
url: /es/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

Muchas de las interfaces SVG DOM se refieren a objetos de la clase SVGPoint. Un SVGPoint es un par de coordenadas (x, y). Cuando se usa en operaciones matriciales, un SVGPoint se trata como un vector de la forma: [x] [y] [1] Si un objeto SVGRect se designa como de solo lectura, intentar asignarlo a uno de sus atributos resultar en una excepción lanzada.

```csharp
public class SVGPoint : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x) { get; set; } | La coordenada X. |
| [Y](../../aspose.svg.datatypes/svgpoint/y) { get; set; } | La coordenada Y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform)(SVGMatrix) | Aplica una transformación de matriz de 2x3 en este objeto SVGPoint y devuelve un nuevo objeto SVGPoint transformado: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring)() | Devuelve unString que representa esta instancia. |

### Ver también

* class [SVGValueType](../svgvaluetype)
* espacio de nombres [Aspose.Svg.DataTypes](../../aspose.svg.datatypes)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
