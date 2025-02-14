---
title: CompositeNodeBase
second_title: Aspose.Note für .NET-API-Referenz
description: Die nicht generische Klasse für Knoten die andere Knoten enthalten können.
type: docs
weight: 30
url: /de/net/aspose.note/compositenodebase/
---
## CompositeNodeBase class

Die nicht generische Klasse für Knoten, die andere Knoten enthalten können.

```csharp
public abstract class CompositeNodeBase : Node, ICompositeNode
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.note/node/document) { get; } | Ruft das Dokument des Knotens ab. |
| virtual [IsComposite](../../aspose.note/node/iscomposite) { get; } | Ruft einen Wert ab, der angibt, ob dieser Knoten zusammengesetzt ist. Wenn wahr, kann der Knoten untergeordnete Knoten haben. |
| [NextSibling](../../aspose.note/node/nextsibling) { get; } | Ruft den nächsten Knoten auf derselben Knotenbaumebene ab. |
| [NodeType](../../aspose.note/node/nodetype) { get; } | Ruft den Knotentyp ab. |
| [ParentNode](../../aspose.note/node/parentnode) { get; } | Ruft den übergeordneten Knoten ab. |
| [PreviousSibling](../../aspose.note/node/previoussibling) { get; } | Ruft den vorherigen Knoten auf derselben Knotenbaumebene ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [Accept](../../aspose.note/node/accept)(DocumentVisitor) | Akzeptiert den Besucher des Knotens. |
| abstract [GetChildNodes&lt;T1&gt;](../../aspose.note/compositenodebase/getchildnodes#getchildnodes_1)() | Alle untergeordneten Knoten nach Knotentyp abrufen. |

### Siehe auch

* class [Node](../node)
* interface [ICompositeNode](../icompositenode)
* namensraum [Aspose.Note](../../aspose.note)
* Montage [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
