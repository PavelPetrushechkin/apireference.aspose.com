﻿---
title: accept method
second_title: Aspose.Words for Python via .NET API Reference
description: "Accepts a visitor."
type: docs
weight: 110
url: /python-net/aspose.words/comment/accept/
---

## accept(visitor) {#documentvisitor}

Accepts a visitor.


```python
def accept(self, visitor: aspose.words.DocumentVisitor):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [DocumentVisitor](../../documentvisitor/) |  |

Enumerates over this node and all of its children. Each node calls a corresponding method on DocumentVisitor.

For more info see the Visitor design pattern.




Calls [DocumentVisitor.visit_comment_start()](../../documentvisitor/visit_comment_start/#comment), then calls [Node.accept()](../../node/accept/#documentvisitor) for all
child nodes of the comment and calls [DocumentVisitor.visit_comment_end()](../../documentvisitor/visit_comment_end/#comment) at the end.



### Returns

True if all nodes were visited; false if DocumentVisitor stopped the operation before visiting all nodes.


### See Also

* module [aspose.words](../../)
* class [Comment](../)

