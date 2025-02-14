---
title: NamedNodeMap
second_title: Referencia de API de Aspose.SVG para .NET
description: Representa colecciones de atributos a los que se puede acceder por nombre.
type: docs
weight: 30
url: /es/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Representa colecciones de atributos a los que se puede acceder por nombre.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item) { get; } | Devuelve el elemento índice-ésimo en el mapa. Si el índice es mayor o igual que el número de nodos en este mapa, esto devuelve nulo. (2 indexers) |
| [Length](../../aspose.svg.collections/namednodemap/length) { get; } | El número de nodos en este mapa. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEnumerator](../../aspose.svg.collections/namednodemap/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem)(string) | Recupera un nodo especificado por nombre. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns)(string, string) | Recupera un nodo especificado por nombre local y URI de espacio de nombres. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem)(string) | Elimina un nodo especificado por nombre. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns)(string, string) | Elimina un nodo especificado por nombre local y URI de espacio de nombres. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem)(Attr) | Agrega un nodo utilizando su atributo nodeName. Si un nodo con ese nombre ya está presente en este mapa, se reemplaza por el nuevo. Reemplazar un nodo por sí mismo no tiene ningún efecto. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns)(Attr) | Agrega un nodo usando su URI de espacio de nombres y nombre local. Si un nodo con ese URI de espacio de nombres y ese nombre local ya está presente en este mapa, se reemplaza por el nuevo. Reemplazar un nodo por sí mismo no tiene ningún efecto. |

### Ver también

* class [DOMObject](../../aspose.svg.dom/domobject)
* class [Attr](../../aspose.svg.dom/attr)
* espacio de nombres [Aspose.Svg.Collections](../../aspose.svg.collections)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
