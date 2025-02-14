﻿---
title: widow_control property
second_title: Aspose.Words for Python via .NET API Reference
description: "True if the first and last lines in the paragraph are to remain on the same page as the rest of the paragraph."
type: docs
weight: 390
url: /python-net/aspose.words/paragraphformat/widow_control/
---

## ParagraphFormat.widow_control property

True if the first and last lines in the paragraph are to remain on the same page as the rest of the paragraph.


### Examples

Shows how to enable widow/orphan control for a paragraph.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# When we write the text that does not fit onto one page, one line may spill over onto the next page.
# The single line that ends up on the next page is called an "Orphan",
# and the previous line where the orphan broke off is called a "Widow".
# We can fix orphans and widows by rearranging text via font size, spacing, or page margins.
# If we wish to preserve our document's dimensions, we can set this flag to "True"
# to push widows onto the same page as their respective orphans.
# Leave this flag as "False" will leave widow/orphan pairs in text.
# Every paragraph has this setting accessible in Microsoft Word via Home -> Paragraph -> Paragraph Settings
# (button on bottom right hand corner of "Paragraph" tab) -> "Widow/Orphan control".
builder.paragraph_format.widow_control = widow_control

# Insert text that produces an orphan and a widow.
builder.font.size = 68
builder.write("Lorem ipsum dolor sit amet, consectetur adipiscing elit, " +
                "sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.")

doc.save(ARTIFACTS_DIR + "ParagraphFormat.widow_control.docx")
```

### See Also

* module [aspose.words](../../)
* class [ParagraphFormat](../)

