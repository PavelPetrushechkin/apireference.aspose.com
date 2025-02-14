﻿---
title: insert_break method
second_title: Aspose.Words for Python via .NET API Reference
description: "Inserts a break of the specified type into the document."
type: docs
weight: 240
url: /python-net/aspose.words/documentbuilder/insert_break/
---

## insert_break(break_type) {#breaktype}

Inserts a break of the specified type into the document.


```python
def insert_break(self, break_type: aspose.words.BreakType):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| break_type | [BreakType](../../breaktype/) |  |

Use this method to insert paragraph, page, column, section or line break into the document.


### Examples

Shows how to create headers and footers in a document using DocumentBuilder.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Specify that we want different headers and footers for first, even and odd pages.
builder.page_setup.different_first_page_header_footer = True
builder.page_setup.odd_and_even_pages_header_footer = True

# Create the headers, then add three pages to the document to display each header type.
builder.move_to_header_footer(aw.HeaderFooterType.HEADER_FIRST)
builder.write("Header for the first page")
builder.move_to_header_footer(aw.HeaderFooterType.HEADER_EVEN)
builder.write("Header for even pages")
builder.move_to_header_footer(aw.HeaderFooterType.HEADER_PRIMARY)
builder.write("Header for all other pages")

builder.move_to_section(0)
builder.writeln("Page1")
builder.insert_break(aw.BreakType.PAGE_BREAK)
builder.writeln("Page2")
builder.insert_break(aw.BreakType.PAGE_BREAK)
builder.writeln("Page3")

doc.save(ARTIFACTS_DIR + "DocumentBuilder.headers_and_footers.docx")
```

Shows how to insert a Table of contents (TOC) into a document using heading styles as entries.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Insert a table of contents for the first page of the document.
# Configure the table to pick up paragraphs with headings of levels 1 to 3.
# Also, set its entries to be hyperlinks that will take us
# to the location of the heading when left-clicked in Microsoft Word.
builder.insert_table_of_contents("\\o \"1-3\" \\h \\z \\u")
builder.insert_break(aw.BreakType.PAGE_BREAK)

# Populate the table of contents by adding paragraphs with heading styles.
# Each such heading with a level between 1 and 3 will create an entry in the table.
builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING1
builder.writeln("Heading 1")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING2
builder.writeln("Heading 1.1")
builder.writeln("Heading 1.2")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING1
builder.writeln("Heading 2")
builder.writeln("Heading 3")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING2
builder.writeln("Heading 3.1")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING3
builder.writeln("Heading 3.1.1")
builder.writeln("Heading 3.1.2")
builder.writeln("Heading 3.1.3")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING4
builder.writeln("Heading 3.1.3.1")
builder.writeln("Heading 3.1.3.2")

builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING2
builder.writeln("Heading 3.2")
builder.writeln("Heading 3.3")

# A table of contents is a field of a type that needs to be updated to show an up-to-date result.
doc.update_fields()
doc.save(ARTIFACTS_DIR + "DocumentBuilder.insert_toc.docx")
```

Shows how to apply and revert page setup settings to sections in a document.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Modify the page setup properties for the builder's current section and add text.
builder.page_setup.orientation = aw.Orientation.LANDSCAPE
builder.page_setup.vertical_alignment = aw.PageVerticalAlignment.CENTER
builder.writeln("This is the first section, which landscape oriented with vertically centered text.")

# If we start a new section using a document builder,
# it will inherit the builder's current page setup properties.
builder.insert_break(aw.BreakType.SECTION_BREAK_NEW_PAGE)

self.assertEqual(aw.Orientation.LANDSCAPE, doc.sections[1].page_setup.orientation)
self.assertEqual(aw.PageVerticalAlignment.CENTER, doc.sections[1].page_setup.vertical_alignment)

# We can revert its page setup properties to their default values using the "ClearFormatting" method.
builder.page_setup.clear_formatting()

self.assertEqual(aw.Orientation.PORTRAIT, doc.sections[1].page_setup.orientation)
self.assertEqual(aw.PageVerticalAlignment.TOP, doc.sections[1].page_setup.vertical_alignment)

builder.writeln("This is the second section, which is in default Letter paper size, portrait orientation and top alignment.")

doc.save(ARTIFACTS_DIR + "PageSetup.clear_formatting.docx")
```

### See Also

* module [aspose.words](../../)
* class [DocumentBuilder](../)

