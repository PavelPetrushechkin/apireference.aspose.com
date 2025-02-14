---
title: SVGListBaseT
second_title: Referencia de API de Aspose.SVG para .NET
description: Esta interfaz define una lista base de todas las listas SVG.
type: docs
weight: 50
url: /es/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

Esta interfaz define una lista base de todas las listas SVG.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento almacenado en la lista. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase`1/item) { get; set; } | Devuelve el elemento índice de la lista. |
| [Length](../../aspose.svg.collections/svglistbase`1/length) { get; } | El número de elementos en la lista. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase`1/numberofitems) { get; } | El número de elementos en la lista. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase`1/appenditem)(T) | Inserta un nuevo elemento al final de la lista. |
| [Clear](../../aspose.svg.collections/svglistbase`1/clear)() | Borra todos los elementos actuales existentes de la lista y el resultado es una lista vacía. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase`1/getenumerator)() | Obtiene el enumerador. |
| [GetItem](../../aspose.svg.collections/svglistbase`1/getitem)(ulong) | Devuelve el elemento especificado de la lista. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [Initialize](../../aspose.svg.collections/svglistbase`1/initialize)(T) | Borra todos los elementos actuales existentes de la lista y reinicializa la lista para contener el único elemento especificado por el parámetro. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase`1/insertitembefore)(T, ulong) | Inserta un nuevo elemento en la lista en la posición especificada. El primer elemento es el número 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase`1/removeitem)(ulong) | Elimina un elemento existente de la lista. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase`1/replaceitem)(T, ulong) | Reemplaza un elemento existente en la lista con un nuevo elemento. |

### Ver también

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype)
* espacio de nombres [Aspose.Svg.Collections](../../aspose.svg.collections)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
