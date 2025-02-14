﻿---
title: TxtSaveOptions class
second_title: Aspose.Words for Python via .NET API Reference
description: "Can be used to specify additional options when saving a document into the [SaveFormat.TEXT](../../aspose.words/saveformat/#TEXT) format."
type: docs
weight: 790
url: /python-net/aspose.words.saving/txtsaveoptions/
---

## TxtSaveOptions class

Can be used to specify additional options when saving a document into the [SaveFormat.TEXT](../../aspose.words/saveformat/#TEXT) format.



**Inheritance:** [TxtSaveOptions](./) → [TxtSaveOptionsBase](../txtsaveoptionsbase/) → [SaveOptions](../saveoptions/)

### Constructors
| Name | Description |
| --- | --- |
| [TxtSaveOptions()](./__init__/#default) | The default constructor. |

### Properties

| Name | Description |
| --- | --- |
| [add_bidi_marks](./add_bidi_marks/) | Specifies whether to add bi-directional marks before each BiDi run when exporting in plain text format. |
| [allow_embedding_post_script_fonts](../saveoptions/allow_embedding_post_script_fonts/) | Gets or sets a boolean value indicating whether to allow embedding fonts with PostScript outlines when embedding TrueType fonts in a document upon it is saved. The default value is **false**.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [default_template](../saveoptions/default_template/) | Gets or sets path to default template (including filename). Default value for this property is **empty string** (System.String.Empty).<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [dml_3d_effects_rendering_mode](../saveoptions/dml_3d_effects_rendering_mode/) | Gets or sets a value determining how 3D effects are rendered.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [dml_effects_rendering_mode](../saveoptions/dml_effects_rendering_mode/) | Gets or sets a value determining how DrawingML effects are rendered.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [dml_rendering_mode](../saveoptions/dml_rendering_mode/) | Gets or sets a value determining how DrawingML shapes are rendered.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [encoding](../txtsaveoptionsbase/encoding/) | Specifies the encoding to use when exporting in text formats.  Default value is **Encoding.UTF8**.<br>(Inherited from [TxtSaveOptionsBase](../txtsaveoptionsbase/)) |
| [export_generator_name](../saveoptions/export_generator_name/) | When true, causes the name and version of Aspose.Words to be embedded into produced files. Default value is **true**.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [export_headers_footers_mode](../txtsaveoptionsbase/export_headers_footers_mode/) | Specifies the way headers and footers are exported to the text formats. Default value is [TxtExportHeadersFootersMode.PRIMARY_ONLY](../txtexportheadersfootersmode/#PRIMARY_ONLY).<br>(Inherited from [TxtSaveOptionsBase](../txtsaveoptionsbase/)) |
| [flat_opc_xml_mapping_only](../saveoptions/flat_opc_xml_mapping_only/) | Gets or sets value determining which document formats are allowed to be mapped by [StructuredDocumentTag.xml_mapping](../../aspose.words.markup/structureddocumenttag/xml_mapping/). By default only [LoadFormat.FLAT_OPC](../../aspose.words/loadformat/#FLAT_OPC) document format is allowed to be mapped.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [force_page_breaks](../txtsaveoptionsbase/force_page_breaks/) | Allows to specify whether the page breaks should be preserved during export.<br>(Inherited from [TxtSaveOptionsBase](../txtsaveoptionsbase/)) |
| [iml_rendering_mode](../saveoptions/iml_rendering_mode/) | Gets or sets a value determining how ink (InkML) objects are rendered.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [list_indentation](./list_indentation/) | Gets a ListIndentation object that specifies how many and which character to use for indentation of list levels. By default it is zero count of character '\\0', that means no indentation. |
| [max_characters_per_line](./max_characters_per_line/) | Gets or sets an integer value that specifies the maximum number of characters per one line. The default value is 0, that means no limit. |
| [memory_optimization](../saveoptions/memory_optimization/) | Gets or sets value determining if memory optimization should be performed before saving the document. Default value for this property is **false**.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [paragraph_break](../txtsaveoptionsbase/paragraph_break/) | Specifies the string to use as a paragraph break when exporting in text formats.<br>(Inherited from [TxtSaveOptionsBase](../txtsaveoptionsbase/)) |
| [preserve_table_layout](./preserve_table_layout/) | Specifies whether the program should attempt to preserve layout of tables when saving in the plain text format. The default value is **false**. |
| [pretty_format](../saveoptions/pretty_format/) | When ``true``, pretty formats output where applicable.  Default value is **false**.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [progress_callback](../saveoptions/progress_callback/) | Called during saving a document and accepts data about saving progress.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [save_format](./save_format/) | Specifies the format in which the document will be saved if this save options object is used. Can only be [SaveFormat.TEXT](../../aspose.words/saveformat/#TEXT). |
| [simplify_list_labels](./simplify_list_labels/) | Specifies whether the program should simplify list labels in case of complex label formatting not being adequately represented by plain text. |
| [temp_folder](../saveoptions/temp_folder/) | Specifies the folder for temporary files used when saving to a DOC or DOCX file. By default this property is ``null`` and no temporary files are used.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [update_created_time_property](../saveoptions/update_created_time_property/) | Gets or sets a value determining whether the [BuiltInDocumentProperties.created_time](../../aspose.words.properties/builtindocumentproperties/created_time/) property is updated before saving. Default value is false;<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [update_fields](../saveoptions/update_fields/) | Gets or sets a value determining if fields of certain types should be updated before saving the document to a fixed page format. Default value for this property is **true**.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [update_last_printed_property](../saveoptions/update_last_printed_property/) | Gets or sets a value determining whether the [BuiltInDocumentProperties.last_printed](../../aspose.words.properties/builtindocumentproperties/last_printed/) property is updated before saving.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [update_last_saved_time_property](../saveoptions/update_last_saved_time_property/) | Gets or sets a value determining whether the [BuiltInDocumentProperties.last_saved_time](../../aspose.words.properties/builtindocumentproperties/last_saved_time/) property is updated before saving.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [update_sdt_content](../saveoptions/update_sdt_content/) | Gets or sets value determining whether content of [StructuredDocumentTag](../../aspose.words.markup/structureddocumenttag/) is updated before saving.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [use_anti_aliasing](../saveoptions/use_anti_aliasing/) | Gets or sets a value determining whether or not to use anti-aliasing for rendering.<br>(Inherited from [SaveOptions](../saveoptions/)) |
| [use_high_quality_rendering](../saveoptions/use_high_quality_rendering/) | Gets or sets a value determining whether or not to use high quality (i.e. slow) rendering algorithms.<br>(Inherited from [SaveOptions](../saveoptions/)) |

### Methods

| Name | Description |
| --- | --- |
|[ create_save_options(save_format)](../saveoptions/create_save_options/#saveformat) | Creates a save options object of a class suitable for the specified save format.<br>(Inherited from [SaveOptions](../saveoptions/)) |
|[ create_save_options(file_name)](../saveoptions/create_save_options/#str) | Creates a save options object of a class suitable for the file extension specified in the given file name.<br>(Inherited from [SaveOptions](../saveoptions/)) |

### Examples

Shows how to save a .txt document with a custom paragraph break.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.writeln("Paragraph 1.")
builder.writeln("Paragraph 2.")
builder.write("Paragraph 3.")

# Create a "TxtSaveOptions" object, which we can pass to the document's "Save" method
# to modify how we save the document to plaintext.
txt_save_options = aw.saving.TxtSaveOptions()

self.assertEqual(aw.SaveFormat.TEXT, txt_save_options.save_format)

# Set the "paragraph_break" to a custom value that we wish to put at the end of every paragraph.
txt_save_options.paragraph_break = " End of paragraph.\n\n\t"

doc.save(ARTIFACTS_DIR + "TxtSaveOptions.paragraph_break.txt", txt_save_options)

with open(ARTIFACTS_DIR + "TxtSaveOptions.paragraph_break.txt", "rb") as file:
    doc_text = file.read().decode("utf-8-sig")

self.assertEqual(
    "Paragraph 1. End of paragraph.\n\n\t" +
    "Paragraph 2. End of paragraph.\n\n\t" +
    "Paragraph 3. End of paragraph.\n\n\t", doc_text)
```

### See Also

* module [aspose.words.saving](../)
* class [TxtSaveOptionsBase](../txtsaveoptionsbase/)

