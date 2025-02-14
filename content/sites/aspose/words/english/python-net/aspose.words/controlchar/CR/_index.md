﻿---
title: CR property
second_title: Aspose.Words for Python via .NET API Reference
description: "Carriage return character: \\x000d or \\r"
type: docs
weight: 50
url: /python-net/aspose.words/controlchar/CR/
---

## ControlChar.CR property

Carriage return character: "\\x000d" or "\\r". Same as [ControlChar.PARAGRAPH_BREAK](../PARAGRAPH_BREAK/).



### Examples

Shows how to use control characters.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert paragraphs with text with DocumentBuilder.
builder.writeln("Hello world!")
builder.writeln("Hello again!")

# Converting the document to text form reveals that control characters
# represent some of the document's structural elements, such as page breaks.
self.assertEqual(f"Hello world!{aw.ControlChar.CR}" +
                 f"Hello again!{aw.ControlChar.CR}" +
                 aw.ControlChar.PAGE_BREAK, doc.get_text())

# When converting a document to string form,
# we can omit some of the control characters with the "strip" method.
self.assertEqual(f"Hello world!{aw.ControlChar.CR}" +
                 "Hello again!", doc.get_text().strip())
```

### See Also

* module [aspose.words](../../)
* class [ControlChar](../)

