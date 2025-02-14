﻿---
title: node_type property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns NodeType.SubDocument"
type: docs
weight: 10
url: /python-net/aspose.words/subdocument/node_type/
---

## SubDocument.node_type property

Returns **NodeType.SubDocument**


### Examples

Shows how to access a master document's subdocument.

```python
doc = aw.Document(MY_DIR + "Master document.docx")

sub_documents = doc.get_child_nodes(aw.NodeType.SUB_DOCUMENT, True)

# This node serves as a reference to an external document, and its contents cannot be accessed.
sub_document = sub_documents[0].as_sub_document()

self.assertFalse(sub_document.is_composite)
```

### See Also

* module [aspose.words](../../)
* class [SubDocument](../)

