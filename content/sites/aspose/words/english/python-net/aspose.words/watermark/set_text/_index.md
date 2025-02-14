﻿---
title: set_text method
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.Watermark.set_text method"
type: docs
weight: 40
url: /python-net/aspose.words/watermark/set_text/
---

## set_text(text) {#str}

Adds Text watermark into the document.


```python
def set_text(self, text: str):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | str |  |

The text length must be in the range from 1 to 200 inclusive.
The text cannot be null or contain only whitespaces.


### Exceptions

| exception | condition |
| --- | --- |
| System.ArgumentOutOfRangeException | Throws when the text length is out of range or the text contains only whitespaces. |
| System.ArgumentNullException | Throws when the text is null. |

## set_text(text, options) {#str_textwatermarkoptions}

Adds Text watermark into the document.


```python
def set_text(self, text: str, options: aspose.words.TextWatermarkOptions):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| text | str |  |
| options | [TextWatermarkOptions](../../textwatermarkoptions/) |  |

The text length must be in the range from 1 to 200 inclusive.
The text cannot be null or contain only whitespaces.


If [TextWatermarkOptions](../../textwatermarkoptions/) is null, the watermark will be set with default options.


### Exceptions

| exception | condition |
| --- | --- |
| System.ArgumentOutOfRangeException | Throws when the text length is out of range or the text contain only whitespaces. |
| System.ArgumentNullException | Throws when the text is null. |

## Examples

Shows how to create a text watermark.

```python
doc = aw.Document()

# Add a plain text watermark.
doc.watermark.set_text("Aspose Watermark")

# If we wish to edit the text formatting using it as a watermark,
# we can do so by passing a TextWatermarkOptions object when creating the watermark.
text_watermark_options = aw.TextWatermarkOptions()
text_watermark_options.font_family = "Arial"
text_watermark_options.font_size = 36
text_watermark_options.color = drawing.Color.black
text_watermark_options.layout = aw.WatermarkLayout.DIAGONAL
text_watermark_options.is_semitrasparent = False

doc.watermark.set_text("Aspose Watermark", text_watermark_options)

doc.save(ARTIFACTS_DIR + "Document.text_watermark.docx")

# We can remove a watermark from a document like this.
if doc.watermark.type == aw.WatermarkType.TEXT:
    doc.watermark.remove()
```

## See Also

* module [aspose.words](../../)
* class [Watermark](../)

