---
title: InsertCell
second_title: Référence de l'API Aspose.HTML pour .NET
description: Insérer un videTD cellule dans cette rangée. Si indice est 1 ou égal au nombre de cellules la nouvelle cellule est ajoutée.
type: docs
weight: 100
url: /fr/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Insérer un vide`TD` cellule dans cette rangée. Si `indice` est -1 ou égal au nombre de cellules, la nouvelle cellule est ajoutée.

```csharp
public HTMLElement InsertCell(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | L'endroit où insérer la cellule, à partir de 0. |

### Return_Value

La cellule nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | INDEX_SIZE_ERR : déclenché si la valeur spécifiée`indice` est supérieur au nombre de cellules ou si l'index est un nombre négatif autre que -1. @version DOM niveau 2 |

### Voir également

* class [HTMLElement](../../htmlelement)
* class [HTMLTableRowElement](../../htmltablerowelement)
* espace de noms [Aspose.Html](../../htmltablerowelement)
* Assemblée [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
