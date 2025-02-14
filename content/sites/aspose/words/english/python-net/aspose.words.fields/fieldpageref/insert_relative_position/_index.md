﻿---
title: insert_relative_position property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets whether to insert a relative position of the bookmarked paragraph."
type: docs
weight: 40
url: /python-net/aspose.words.fields/fieldpageref/insert_relative_position/
---

## FieldPageRef.insert_relative_position property

Gets or sets whether to insert a relative position of the bookmarked paragraph.


### Examples

Shows to insert PAGEREF fields to display the relative location of bookmarks.

```python
def test_field_page_ref(self):

    doc = aw.Document()
    builder = aw.DocumentBuilder(doc)

    ExField.insert_and_name_bookmark(builder, "MyBookmark1")

    # Insert a PAGEREF field that displays what page a bookmark is on.
    # Set the InsertHyperlink flag to make the field also function as a clickable link to the bookmark.
    self.assertEqual(" PAGEREF  MyBookmark3 \\h",
        ExField.insert_field_page_ref(builder, "MyBookmark3", True, False, "Hyperlink to Bookmark3, on page: ").get_field_code())

    # We can use the \p flag to get the PAGEREF field to display
    # the bookmark's position relative to the position of the field.
    # Bookmark1 is on the same page and above this field, so this field's displayed result will be "above".
    self.assertEqual(" PAGEREF  MyBookmark1 \\h \\p",
        ExField.insert_field_page_ref(builder, "MyBookmark1", True, True, "Bookmark1 is ").get_field_code())

    # Bookmark2 will be on the same page and below this field, so this field's displayed result will be "below".
    self.assertEqual(" PAGEREF  MyBookmark2 \\h \\p",
        ExField.insert_field_page_ref(builder, "MyBookmark2", True, True, "Bookmark2 is ").get_field_code())

    # Bookmark3 will be on a different page, so the field will display "on page 2".
    self.assertEqual(" PAGEREF  MyBookmark3 \\h \\p",
        ExField.insert_field_page_ref(builder, "MyBookmark3", True, True, "Bookmark3 is ").get_field_code())

    ExField.insert_and_name_bookmark(builder, "MyBookmark2")
    builder.insert_break(aw.BreakType.PAGE_BREAK)
    ExField.insert_and_name_bookmark(builder, "MyBookmark3")

    doc.update_fields()
    doc.save(ARTIFACTS_DIR + "Field.field_page_ref.docx")

@staticmethod
def insert_field_page_ref(builder: aw.DocumentBuilder, bookmark_name: str, insert_hyperlink: bool, insert_relative_position: bool, text_before: str) -> aw.fields.FieldPageRef:
    """Uses a document builder to insert a PAGEREF field and sets its properties."""

    builder.write(text_before)

    field = builder.insert_field(aw.fields.FieldType.FIELD_PAGE_REF, True).as_field_page_ref()
    field.bookmark_name = bookmark_name
    field.insert_hyperlink = insert_hyperlink
    field.insert_relative_position = insert_relative_position
    builder.writeln()

    return field

@staticmethod
def insert_and_name_bookmark(builder: aw.DocumentBuilder, bookmark_name: str):
    """Uses a document builder to insert a named bookmark."""

    builder.start_bookmark(bookmark_name)
    builder.writeln(f"Contents of bookmark \"{bookmark_name}\".")
    builder.end_bookmark(bookmark_name)
```

### See Also

* module [aspose.words.fields](../../)
* class [FieldPageRef](../)

