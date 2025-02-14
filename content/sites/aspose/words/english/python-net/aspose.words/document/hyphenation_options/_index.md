﻿---
title: hyphenation_options property
second_title: Aspose.Words for Python via .NET API Reference
description: "Provides access to document hyphenation options."
type: docs
weight: 210
url: /python-net/aspose.words/document/hyphenation_options/
---

## Document.hyphenation_options property

Provides access to document hyphenation options.


### Examples

Shows how to configure automatic hyphenation.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.font.size = 24
builder.writeln("Lorem ipsum dolor sit amet, consectetur adipiscing elit, " +
                "sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.")

doc.hyphenation_options.auto_hyphenation = True
doc.hyphenation_options.consecutive_hyphen_limit = 2
doc.hyphenation_options.hyphenation_zone = 720
doc.hyphenation_options.hyphenate_caps = True

doc.save(ARTIFACTS_DIR + "Document.hyphenation_options.docx")
```

### See Also

* module [aspose.words](../../)
* class [Document](../)

