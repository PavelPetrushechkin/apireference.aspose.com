﻿---
title: accept method
second_title: Aspose.Words for Python via .NET API Reference
description: "Accepts a visitor."
type: docs
weight: 60
url: /python-net/aspose.words.buildingblocks/glossarydocument/accept/
---

## accept(visitor) {#documentvisitor}

Accepts a visitor.


```python
def accept(self, visitor: aspose.words.DocumentVisitor):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [DocumentVisitor](../../../aspose.words/documentvisitor/) |  |

Enumerates over this node and all of its children. Each node calls a corresponding method on DocumentVisitor.

For more info see the Visitor design pattern.




Calls [DocumentVisitor.visit_glossary_document_start()](../../../aspose.words/documentvisitor/visit_glossary_document_start/#glossarydocument), then calls [Node.accept()](../../../aspose.words/node/accept/#documentvisitor) 
for all child nodes of this node and then calls [DocumentVisitor.visit_glossary_document_end()](../../../aspose.words/documentvisitor/visit_glossary_document_end/#glossarydocument) 
at the end.




Note: A glossary document node and its children are not visited when you execute a
Visitor over a [Document](../../../aspose.words/document/). If you want to execute a Visitor over a
glossary document, you need to call [GlossaryDocument.accept()](./#documentvisitor).





### Returns

True if all nodes were visited; false if DocumentVisitor stopped the operation before visiting all nodes.


### See Also

* module [aspose.words.buildingblocks](../../)
* class [GlossaryDocument](../)

