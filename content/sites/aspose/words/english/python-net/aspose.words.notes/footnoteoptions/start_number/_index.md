﻿---
title: start_number property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the starting number or character for the first automatically numbered footnotes."
type: docs
weight: 50
url: /python-net/aspose.words.notes/footnoteoptions/start_number/
---

## FootnoteOptions.start_number property

Specifies the starting number or character for the first automatically numbered footnotes.

This property has effect only when [FootnoteOptions.restart_rule](../restart_rule/) is set to
[FootnoteNumberingRule.CONTINUOUS](../../footnotenumberingrule/#CONTINUOUS).




### Examples

Shows how to set a number at which the document begins the footnote/endnote count.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Footnotes and endnotes are a way to attach a reference or a side comment to text
# that does not interfere with the main body text's flow.
# Inserting a footnote/endnote adds a small superscript reference symbol
# at the main body text where we insert the footnote/endnote.
# Each footnote/endnote also creates an entry, which consists of a symbol
# that matches the reference symbol in the main body text.
# The reference text that we pass to the document builder's "insert_endnote" method.
# Footnote entries, by default, show up at the bottom of each page that contains
# their reference symbols, and endnotes show up at the end of the document.
builder.write("Text 1. ")
builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote 1.")
builder.write("Text 2. ")
builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote 2.")
builder.write("Text 3. ")
builder.insert_footnote(aw.notes.FootnoteType.FOOTNOTE, "Footnote 3.")

builder.insert_paragraph()

builder.write("Text 1. ")
builder.insert_footnote(aw.notes.FootnoteType.ENDNOTE, "Endnote 1.")
builder.write("Text 2. ")
builder.insert_footnote(aw.notes.FootnoteType.ENDNOTE, "Endnote 2.")
builder.write("Text 3. ")
builder.insert_footnote(aw.notes.FootnoteType.ENDNOTE, "Endnote 3.")

# By default, the reference symbol for each footnote and endnote is its index
# among all the document's footnotes/endnotes. Each document maintains separate counts
# for footnotes and for endnotes, which both begin at 1.
self.assertEqual(1, doc.footnote_options.start_number)
self.assertEqual(1, doc.endnote_options.start_number)

# We can use the "start_number" property to get the document to
# begin a footnote or endnote count at a different number.
doc.endnote_options.number_style = aw.NumberStyle.ARABIC
doc.endnote_options.start_number = 50

doc.save(ARTIFACTS_DIR + "InlineStory.start_number.docx")
```

### See Also

* module [aspose.words.notes](../../)
* class [FootnoteOptions](../)

