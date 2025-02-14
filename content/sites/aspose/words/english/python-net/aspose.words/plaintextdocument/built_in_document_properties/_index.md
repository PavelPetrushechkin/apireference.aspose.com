﻿---
title: built_in_document_properties property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets [PlainTextDocument.built_in_document_properties](./) of the document."
type: docs
weight: 20
url: /python-net/aspose.words/plaintextdocument/built_in_document_properties/
---

## PlainTextDocument.built_in_document_properties property

Gets [PlainTextDocument.built_in_document_properties](./) of the document.



### Examples

Shows how to load the contents of a Microsoft Word document in plaintext and then access the original document's built-in properties.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.writeln("Hello world!")
doc.built_in_document_properties.author = "John Doe"

doc.save(ARTIFACTS_DIR + "PlainTextDocument.built_in_properties.docx")

plaintext = aw.PlainTextDocument(ARTIFACTS_DIR + "PlainTextDocument.built_in_properties.docx")

self.assertEqual("Hello world!", plaintext.text.strip())
self.assertEqual("John Doe", plaintext.built_in_document_properties.author)
```

### See Also

* module [aspose.words](../../)
* class [PlainTextDocument](../)

