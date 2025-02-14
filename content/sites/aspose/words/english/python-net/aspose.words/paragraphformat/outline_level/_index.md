﻿---
title: outline_level property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the outline level of the paragraph in the document."
type: docs
weight: 240
url: /python-net/aspose.words/paragraphformat/outline_level/
---

## ParagraphFormat.outline_level property

Specifies the outline level of the paragraph in the document.


### Examples

Shows how to configure paragraph outline levels to create collapsible text.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Each paragraph has an OutlineLevel, which could be any number from 1 to 9, or at the default "BODY_TEXT" value.
# Setting the property to one of the numbered values will show an arrow to the left
# of the beginning of the paragraph.
builder.paragraph_format.outline_level = aw.OutlineLevel.LEVEL1
builder.writeln("Paragraph outline level 1.")

# Level 1 is the topmost level. If there is a paragraph with a lower level below a paragraph with a higher level,
# collapsing the higher-level paragraph will collapse the lower level paragraph.
builder.paragraph_format.outline_level = aw.OutlineLevel.LEVEL2
builder.writeln("Paragraph outline level 2.")

# Two paragraphs of the same level will not collapse each other,
# and the arrows do not collapse the paragraphs they point to.
builder.paragraph_format.outline_level = aw.OutlineLevel.LEVEL3
builder.writeln("Paragraph outline level 3.")
builder.writeln("Paragraph outline level 3.")

# The default "BODY_TEXT" value is the lowest, which a paragraph of any level can collapse.
builder.paragraph_format.outline_level = aw.OutlineLevel.BODY_TEXT
builder.writeln("Paragraph at main text level.")

doc.save(ARTIFACTS_DIR + "ParagraphFormat.paragraph_outline_level.docx")
```

### See Also

* module [aspose.words](../../)
* class [ParagraphFormat](../)

