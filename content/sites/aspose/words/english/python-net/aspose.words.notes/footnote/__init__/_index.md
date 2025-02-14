﻿---
title: Footnote constructor
second_title: Aspose.Words for Python via .NET API Reference
description: "Initializes an instance of the Footnote class."
type: docs
weight: 10
url: /python-net/aspose.words.notes/footnote/__init__/
---

## Footnote(doc, footnote_type) {#documentbase_footnotetype}

Initializes an instance of the **Footnote** class.



```python
def __init__(self, doc: aspose.words.DocumentBase, footnote_type: aspose.words.notes.FootnoteType):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| doc | [DocumentBase](../../../aspose.words/documentbase/) |  |
| footnote_type | [FootnoteType](../../footnotetype/) |  |

When **Footnote** is created, it belongs to the specified document, but is not
yet part of the document and **ParentNode** is null.

To append **Footnote** to the document use InsertAfter or InsertBefore
on the paragraph where you want the footnote inserted.




### Examples

Shows how to insert and customize footnotes.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Add text, and reference it with a footnote. This footnote will place a small superscript reference
# mark after the text that it references and create an entry below the main body text at the bottom of the page.
# This entry will contain the footnote's reference mark and the reference text,
# which we will pass to the document builder's "insert_footnote" method.
builder.write("Main body text.")
footnote = builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote text.")

# If this property is set to "True", then our footnote's reference mark
# will be its index among all the section's footnotes.
# This is the first footnote, so the reference mark will be "1".
self.assertTrue(footnote.is_auto)

# We can move the document builder inside the footnote to edit its reference text.
builder.move_to(footnote.first_paragraph)
builder.write(" More text added by a DocumentBuilder.")
builder.move_to_document_end()

self.assertEqual("\u0002 Footnote text. More text added by a DocumentBuilder.", footnote.get_text().strip())

builder.write(" More main body text.")
footnote = builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote text.")

# We can set a custom reference mark which the footnote will use instead of its index number.
footnote.reference_mark = "RefMark"

self.assertFalse(footnote.is_auto)

# A bookmark with the "is_auto" flag set to True will still show its real index
# even if previous bookmarks display custom reference marks, so this bookmark's reference mark will be a "3".
builder.write(" More main body text.")
footnote = builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote text.")

self.assertTrue(footnote.is_auto)

doc.save(ARTIFACTS_DIR + "InlineStory.add_footnote.docx")
```

### See Also

* module [aspose.words.notes](../../)
* class [Footnote](../)

