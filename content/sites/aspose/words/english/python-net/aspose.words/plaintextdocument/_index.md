﻿---
title: PlainTextDocument class
second_title: Aspose.Words for Python via .NET API Reference
description: "Allows to extract plain-text representation of the document's content."
type: docs
weight: 870
url: /python-net/aspose.words/plaintextdocument/
---

## PlainTextDocument class

Allows to extract plain-text representation of the document's content.


### Constructors
| Name | Description |
| --- | --- |
| [PlainTextDocument(file_name)](./__init__/#str) | Creates a plain text document from a file. Automatically detects the file format. |
| [PlainTextDocument(file_name, load_options)](./__init__/#str_loadoptions) | Creates a plain text document from a file. Allows to specify additional options such as an encryption password. |
| [PlainTextDocument(stream)](./__init__/#bytesio) | Creates a plain text document from a stream. Automatically detects the file format. |
| [PlainTextDocument(stream, load_options)](./__init__/#bytesio_loadoptions) | Creates a plain text document from a stream. Allows to specify additional options such as an encryption password. |

### Properties

| Name | Description |
| --- | --- |
| [built_in_document_properties](./built_in_document_properties/) | Gets [PlainTextDocument.built_in_document_properties](./built_in_document_properties/) of the document. |
| [custom_document_properties](./custom_document_properties/) | Gets [PlainTextDocument.custom_document_properties](./custom_document_properties/) of the document. |
| [text](./text/) | Gets textual content of the document concatenated as a string. |

### Examples

Shows how to load the contents of a Microsoft Word document in plaintext.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
builder.writeln("Hello world!")

doc.save(ARTIFACTS_DIR + "PlainTextDocument.load.docx")

plaintext = aw.PlainTextDocument(ARTIFACTS_DIR + "PlainTextDocument.load.docx")

self.assertEqual("Hello world!", plaintext.text.strip())
```

### See Also

* module [aspose.words](../)

