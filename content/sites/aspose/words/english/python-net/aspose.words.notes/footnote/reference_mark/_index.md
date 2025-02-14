﻿---
title: reference_mark property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets/sets custom reference mark to be used for this footnote"
type: docs
weight: 50
url: /python-net/aspose.words.notes/footnote/reference_mark/
---

## Footnote.reference_mark property

Gets/sets custom reference mark to be used for this footnote.
Default value is **empty string** (System.String.Empty), meaning auto-numbered footnotes are used.


If this property is set to **empty string** (System.String.Empty) or null, then [Footnote.is_auto](../is_auto/) property will automatically be set to true, 
if set to anything else then [Footnote.is_auto](../is_auto/) will be set to false.


RTF-format can only store 1 symbol as custom reference mark, so upon export only the first symbol will be written others will be discard.




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

