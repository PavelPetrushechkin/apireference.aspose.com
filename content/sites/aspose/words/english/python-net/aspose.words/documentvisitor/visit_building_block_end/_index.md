﻿---
title: visit_building_block_end method
second_title: Aspose.Words for Python via .NET API Reference
description: "Called when enumeration of a building block has ended."
type: docs
weight: 60
url: /python-net/aspose.words/documentvisitor/visit_building_block_end/
---

## visit_building_block_end(block) {#buildingblock}

Called when enumeration of a building block has ended.


```python
def visit_building_block_end(self, block: aspose.words.buildingblocks.BuildingBlock):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| block | [BuildingBlock](../../../aspose.words.buildingblocks/buildingblock/) |  |

Note: A building block node and its children are not visited when you execute a
Visitor over a [Document](../../document/). If you want to execute a Visitor over a
building block, you need to execute the visitor over [GlossaryDocument](../../../aspose.words.buildingblocks/glossarydocument/) or
call [BuildingBlock.accept()](../../../aspose.words.buildingblocks/buildingblock/accept/#documentvisitor).





### Returns

A [VisitorAction](../../visitoraction/) value that specifies how to continue the enumeration.


### See Also

* module [aspose.words](../../)
* class [DocumentVisitor](../)

