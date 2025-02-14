---
title: NextNode
second_title: Aspose.SVG for .NET API 参考
description: 返回集合中的下一个节点并将 迭代器在集合中的位置提前创建 NodeIterator 后 第一次调用 nextNode 返回 集合中的第一个节点
type: docs
weight: 40
url: /zh/net/aspose.svg.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

返回集合中的下一个节点，并将 迭代器在集合中的位置提前。创建 NodeIterator 后， 第一次调用 nextNode() 返回 集合中的第一个节点。

```csharp
public Node NextNode()
```

### 返回值

被迭代的集合中的下一个节点，或者 如果该集合中没有更多成员，则为 null。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | INVALID_STATE_ERR：如果在调用 detach 方法之后调用此方法，则引发。 |

### 也可以看看

* class [Node](../../../aspose.svg.dom/node)
* interface [INodeIterator](../../inodeiterator)
* 命名空间 [Aspose.Svg.Dom.Traversal](../../inodeiterator)
* 部件 [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
