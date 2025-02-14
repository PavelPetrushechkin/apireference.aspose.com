﻿---
title: text_effect property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the font animation effect."
type: docs
weight: 450
url: /python-net/aspose.words/font/text_effect/
---

## Font.text_effect property

Gets or sets the font animation effect.


### Examples

Shows how to apply a visual effect to a run.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.font.size = 36
builder.font.text_effect = aw.TextEffect.SPARKLE_TEXT

builder.writeln("Text with a sparkle effect.")

# Older versions of Microsoft Word only support font animation effects.
doc.save(ARTIFACTS_DIR + "Font.sparkling_text.doc")
```

### See Also

* module [aspose.words](../../)
* class [Font](../)

