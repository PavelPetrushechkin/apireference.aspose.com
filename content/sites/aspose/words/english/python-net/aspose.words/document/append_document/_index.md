﻿---
title: append_document method
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.Document.append_document method"
type: docs
weight: 510
url: /python-net/aspose.words/document/append_document/
---

## append_document(src_doc, import_format_mode) {#document_importformatmode}

Appends the specified document to the end of this document.


```python
def append_document(self, src_doc: aspose.words.Document, import_format_mode: aspose.words.ImportFormatMode):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| src_doc | [Document](../) |  |
| import_format_mode | [ImportFormatMode](../../importformatmode/) |  |

## append_document(src_doc, import_format_mode, import_format_options) {#document_importformatmode_importformatoptions}

Appends the specified document to the end of this document.


```python
def append_document(self, src_doc: aspose.words.Document, import_format_mode: aspose.words.ImportFormatMode, import_format_options: aspose.words.ImportFormatOptions):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| src_doc | [Document](../) |  |
| import_format_mode | [ImportFormatMode](../../importformatmode/) |  |
| import_format_options | [ImportFormatOptions](../../importformatoptions/) |  |

## Examples

Shows how to append a document to the end of another document.

```python
src_doc = aw.Document()
src_doc.first_section.body.append_paragraph("Source document text. ")

dst_doc = aw.Document()
dst_doc.first_section.body.append_paragraph("Destination document text. ")

# Append the source document to the destination document while preserving its formatting,
# then save the source document to the local file system.
dst_doc.append_document(src_doc, aw.ImportFormatMode.KEEP_SOURCE_FORMATTING)

dst_doc.save(ARTIFACTS_DIR + "Document.append_document.docx")
```

Shows how to append all the documents in a folder to the end of a template document.

```python
dst_doc = aw.Document()

builder = aw.DocumentBuilder(dst_doc)
builder.paragraph_format.style_identifier = aw.StyleIdentifier.HEADING1
builder.writeln("Template Document")
builder.paragraph_format.style_identifier = aw.StyleIdentifier.NORMAL
builder.writeln("Some content here")

# Append all unencrypted documents with the .doc extension
# from our local file system directory to the base document.
doc_files = glob.glob(MY_DIR + "*.doc")
for file_name in doc_files:
    info = aw.FileFormatUtil.detect_file_format(file_name)
    if info.is_encrypted:
        continue

    src_doc = aw.Document(file_name)
    dst_doc.append_document(src_doc, aw.ImportFormatMode.USE_DESTINATION_STYLES)

dst_doc.save(ARTIFACTS_DIR + "Document.append_all_documents_in_folder.doc")
```

Shows how to manage list style clashes while appending a document.

```python
# Load a document with text in a custom style and clone it.
src_doc = aw.Document(MY_DIR + "Custom list numbering.docx")
dst_doc = src_doc.clone()

# We now have two documents, each with an identical style named "CustomStyle".
# Change the text color for one of the styles to set it apart from the other.
dst_doc.styles.get_by_name("CustomStyle").font.color = drawing.Color.dark_red

# If there is a clash of list styles, apply the list format of the source document.
# Set the "keep_source_numbering" property to "False" to not import any list numbers into the destination document.
# Set the "keep_source_numbering" property to "True" import all clashing
# list style numbering with the same appearance that it had in the source document.
options = aw.ImportFormatOptions()
options.keep_source_numbering = keep_source_numbering

# Joining two documents that have different styles that share the same name causes a style clash.
# We can specify an import format mode while appending documents to resolve this clash.
dst_doc.append_document(src_doc, aw.ImportFormatMode.KEEP_DIFFERENT_STYLES, options)
dst_doc.update_list_labels()

dst_doc.save(ARTIFACTS_DIR + "DocumentBuilder.append_document_and_resolve_styles.docx")
```

Shows how to manage list style clashes while inserting a document.

```python
dst_doc = aw.Document()
builder = aw.DocumentBuilder(dst_doc)
builder.insert_break(aw.BreakType.PARAGRAPH_BREAK)

dst_doc.lists.add(aw.lists.ListTemplate.NUMBER_DEFAULT)

builder.list_format.list = dst_doc.lists[0]

for i in range(1, 16):
    builder.write(f"List Item {i}\n")

attach_doc = dst_doc.clone(True).as_document()

# If there is a clash of list styles, apply the list format of the source document.
# Set the "keep_source_numbering" property to "False" to not import any list numbers into the destination document.
# Set the "keep_source_numbering" property to "True" import all clashing
# list style numbering with the same appearance that it had in the source document.
import_options = aw.ImportFormatOptions()
import_options.keep_source_numbering = keep_source_numbering

builder.insert_break(aw.BreakType.SECTION_BREAK_NEW_PAGE)
builder.insert_document(attach_doc, aw.ImportFormatMode.KEEP_SOURCE_FORMATTING, import_options)

dst_doc.save(ARTIFACTS_DIR + "DocumentBuilder.insert_document_and_resolve_styles.docx")
```

Shows how to manage list style clashes while appending a clone of a document to itself.

```python
src_doc = aw.Document(MY_DIR + "List item.docx")
dst_doc = aw.Document(MY_DIR + "List item.docx")

# If there is a clash of list styles, apply the list format of the source document.
# Set the "keep_source_numbering" property to "False" to not import any list numbers into the destination document.
# Set the "keep_source_numbering" property to "True" import all clashing
# list style numbering with the same appearance that it had in the source document.
builder = aw.DocumentBuilder(dst_doc)
builder.move_to_document_end()
builder.insert_break(aw.BreakType.SECTION_BREAK_NEW_PAGE)

options = aw.ImportFormatOptions()
options.keep_source_numbering = keep_source_numbering
builder.insert_document(src_doc, aw.ImportFormatMode.KEEP_SOURCE_FORMATTING, options)

dst_doc.update_list_labels()
```

## See Also

* module [aspose.words](../../)
* class [Document](../)

