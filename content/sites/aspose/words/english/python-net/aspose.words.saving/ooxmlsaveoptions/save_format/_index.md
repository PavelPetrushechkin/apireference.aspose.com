﻿---
title: save_format property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the format in which the document will be saved if this save options object is used"
type: docs
weight: 60
url: /python-net/aspose.words.saving/ooxmlsaveoptions/save_format/
---

## OoxmlSaveOptions.save_format property

Specifies the format in which the document will be saved if this save options object is used.
Can be [SaveFormat.DOCX](../../../aspose.words/saveformat/#DOCX), [SaveFormat.DOCM](../../../aspose.words/saveformat/#DOCM),
[SaveFormat.DOTX](../../../aspose.words/saveformat/#DOTX), [SaveFormat.DOTM](../../../aspose.words/saveformat/#DOTM) or [SaveFormat.FLAT_OPC](../../../aspose.words/saveformat/#FLAT_OPC).



### Examples

Shows how to set an OOXML compliance specification for a saved document to adhere to.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

# If we configure compatibility options to comply with Microsoft Word 2003,
# inserting an image will define its shape using VML.
doc.compatibility_options.optimize_for(aw.settings.MsWordVersion.WORD2003)
builder.insert_image(IMAGE_DIR + "Transparent background logo.png")

self.assertEqual(aw.drawing.ShapeMarkupLanguage.VML, doc.get_child(aw.NodeType.SHAPE, 0, True).as_shape().markup_language)

# The "ISO/IEC 29500:2008" OOXML standard does not support VML shapes.
# If we set the "compliance" property of the SaveOptions object to "OoxmlCompliance.ISO29500_2008_STRICT",
# any document we save while passing this object will have to follow that standard.
save_options = aw.saving.OoxmlSaveOptions()
save_options.compliance = aw.saving.OoxmlCompliance.ISO29500_2008_STRICT
save_options.save_format = aw.SaveFormat.DOCX

doc.save(ARTIFACTS_DIR + "OoxmlSaveOptions.iso29500_strict.docx", save_options)

# Our saved document defines the shape using DML to adhere to the "ISO/IEC 29500:2008" OOXML standard.
doc = aw.Document(ARTIFACTS_DIR + "OoxmlSaveOptions.iso29500_strict.docx")

self.assertEqual(aw.drawing.ShapeMarkupLanguage.DML, doc.get_child(aw.NodeType.SHAPE, 0, True).as_shape().markup_language)
```

### See Also

* module [aspose.words.saving](../../)
* class [OoxmlSaveOptions](../)

