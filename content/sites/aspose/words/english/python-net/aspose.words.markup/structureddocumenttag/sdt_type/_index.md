﻿---
title: sdt_type property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets type of this Structured document tag."
type: docs
weight: 250
url: /python-net/aspose.words.markup/structureddocumenttag/sdt_type/
---

## StructuredDocumentTag.sdt_type property

Gets type of this **Structured document tag**.



### Examples

Shows how to get the type of a structured document tag.

```python
doc = aw.Document(MY_DIR + "Structured document tags.docx")

sd_tags = [node.as_structured_document_tag() for node in doc.get_child_nodes(aw.NodeType.STRUCTURED_DOCUMENT_TAG, True)]

self.assertEqual(aw.markup.SdtType.REPEATING_SECTION, sd_tags[0].sdt_type)
self.assertEqual(aw.markup.SdtType.REPEATING_SECTION_ITEM, sd_tags[1].sdt_type)
self.assertEqual(aw.markup.SdtType.RICH_TEXT, sd_tags[2].sdt_type)
```

### See Also

* module [aspose.words.markup](../../)
* class [StructuredDocumentTag](../)

