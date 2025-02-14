﻿---
title: is_path_relative property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets whether the path is relative to the current document."
type: docs
weight: 30
url: /python-net/aspose.words.fields/fieldrd/is_path_relative/
---

## FieldRD.is_path_relative property

Gets or sets whether the path is relative to the current document.


### Examples

Shows to use the RD field to create a table of contents entries from headings in other documents.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# Use a document builder to insert a table of contents,
# and then add one entry for the table of contents on the following page.
builder.insert_field(aw.fields.FieldType.FIELD_TOC, True)
builder.insert_break(aw.BreakType.PAGE_BREAK)
builder.current_paragraph.paragraph_format.style_name = "Heading 1"
builder.writeln("TOC entry from within this document")

# Insert an RD field, which references another local file system document in its FileName property.
# The TOC will also now accept all headings from the referenced document as entries for its table.
field = builder.insert_field(aw.fields.FieldType.FIELD_REF_DOC, True).as_field_rd()
field.file_name = "ReferencedDocument.docx"
field.is_path_relative = True

self.assertEqual(" RD  ReferencedDocument.docx \\f", field.get_field_code())

# Create the document that the RD field is referencing and insert a heading.
# This heading will show up as an entry in the TOC field in our first document.
referenced_doc = aw.Document()
ref_doc_builder = aw.DocumentBuilder(referenced_doc)
ref_doc_builder.current_paragraph.paragraph_format.style_name = "Heading 1"
ref_doc_builder.writeln("TOC entry from referenced document")
referenced_doc.save(ARTIFACTS_DIR + "ReferencedDocument.docx")

doc.update_fields()
doc.save(ARTIFACTS_DIR + "Field.field_rd.docx")
```

### See Also

* module [aspose.words.fields](../../)
* class [FieldRD](../)

