﻿---
title: emphasis_mark property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the emphasis mark applied to this formatting."
type: docs
weight: 110
url: /python-net/aspose.words/font/emphasis_mark/
---

## Font.emphasis_mark property

Gets or sets the emphasis mark applied to this formatting.


### Examples

Shows how to add additional character rendered above/below the glyph-character.

```python
builder = aw.DocumentBuilder()

# Possible types of emphasis mark:
# https://apireference.aspose.com/words/net/aspose.words/emphasismark
builder.font.emphasis_mark = emphasis_mark

builder.write("Emphasis text")
builder.writeln()
builder.font.clear_formatting()
builder.write("Simple text")

builder.document.save(ARTIFACTS_DIR + "Fonts.set_emphasis_mark.docx")
```

### See Also

* module [aspose.words](../../)
* class [Font](../)

