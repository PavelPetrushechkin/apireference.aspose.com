---
title: InsertItemBefore
second_title: Référence de l'API Aspose.SVG pour .NET
description: Insère un nouvel élément dans la liste à la position spécifiée. Le premier élément porte le numéro 0.
type: docs
weight: 90
url: /fr/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Insère un nouvel élément dans la liste à la position spécifiée. Le premier élément porte le numéro 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newItem | T | L'élément qui doit être inséré dans la liste. |
| index | UInt64 | Index de l'élément avant lequel le nouvel élément doit être inséré. Le premier élément porte le numéro 0. Si l'index est égal à 0, alors le nouvel élément est inséré au début de la liste. Si l'index est supérieur ou égal à numberOfItems, le nouvel élément est ajouté à la fin de la liste. |

### Return_Value

L'élément inséré.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err). Levé lorsque la liste ne peut pas être modifiée. |

### Voir également

* class [SVGListBase&lt;T&gt;](../../svglistbase-1)
* espace de noms [Aspose.Svg.Collections](../../svglistbase-1)
* Assemblée [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
