﻿---
title: get_embedded_font method
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets a specific embedded font file."
type: docs
weight: 80
url: /python-net/aspose.words.fonts/fontinfo/get_embedded_font/
---

## get_embedded_font(format, style) {#embeddedfontformat_embeddedfontstyle}

Gets a specific embedded font file.


```python
def get_embedded_font(self, format: aspose.words.fonts.EmbeddedFontFormat, style: aspose.words.fonts.EmbeddedFontStyle):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | [EmbeddedFontFormat](../../embeddedfontformat/) |  |
| style | [EmbeddedFontStyle](../../embeddedfontstyle/) |  |

### Returns

Returns ``null`` if the specified font is not embedded.


### Examples

Shows how to extract an embedded font from a document, and save it to the local file system.

```python
doc = aw.Document(MY_DIR + "Embedded font.docx")

embedded_font = doc.font_infos.get_by_name("Alte DIN 1451 Mittelschrift")
embedded_font_bytes = embedded_font.get_embedded_font(aw.fonts.EmbeddedFontFormat.OPEN_TYPE, aw.fonts.EmbeddedFontStyle.REGULAR)

with open(ARTIFACTS_DIR + "Alte DIN 1451 Mittelschrift.ttf", "wb") as file:
    file.write(embedded_font_bytes)

# Embedded font formats may be different in other formats such as .doc.
# We need to know the correct format before we can extract the font.
doc = aw.Document(MY_DIR + "Embedded font.doc")

self.assertIsNone(doc.font_infos.get_by_name("Alte DIN 1451 Mittelschrift").get_embedded_font(aw.fonts.EmbeddedFontFormat.OPEN_TYPE, aw.fonts.EmbeddedFontStyle.REGULAR))
self.assertIsNotNone(doc.font_infos.get_by_name("Alte DIN 1451 Mittelschrift").get_embedded_font(aw.fonts.EmbeddedFontFormat.EMBEDDED_OPEN_TYPE, aw.fonts.EmbeddedFontStyle.REGULAR))

# Also, we can convert embedded OpenType format, which comes from .doc documents, to OpenType.
embedded_font_bytes = doc.font_infos.get_by_name("Alte DIN 1451 Mittelschrift").get_embedded_font_as_open_type(aw.fonts.EmbeddedFontStyle.REGULAR)

with open(ARTIFACTS_DIR + "Alte DIN 1451 Mittelschrift.otf", "wb") as file:
    file.write(embedded_font_bytes)
```

### See Also

* module [aspose.words.fonts](../../)
* class [FontInfo](../)

