﻿---
title: font_settings property
second_title: Aspose.Words for Python via .NET API Reference
description: "Allows to specify document font settings."
type: docs
weight: 70
url: /python-net/aspose.words.loading/loadoptions/font_settings/
---

## LoadOptions.font_settings property

Allows to specify document font settings.

When loading some formats, Aspose.Words may require to resolve the fonts. For example, when loading HTML documents Aspose.Words
may resolve the fonts to perform font fallback.

If set to null, default static font settings [FontSettings.default_instance](../../../aspose.words.fonts/fontsettings/default_instance/) will be used.

The default value is null.




### Examples

Shows how to designate font substitutes during loading.

```python
load_options = aw.loading.LoadOptions()
load_options.font_settings = aw.fonts.FontSettings()

# Set a font substitution rule for a LoadOptions object.
# If the document we are loading uses a font which we do not have,
# this rule will substitute the unavailable font with one that does exist.
# In this case, all uses of the "MissingFont" will convert to "Comic Sans MS".
substitution_rule = load_options.font_settings.substitution_settings.table_substitution
substitution_rule.add_substitutes("MissingFont", ["Comic Sans MS"])

doc = aw.Document(MY_DIR + "Missing font.html", load_options)

# At this point such text will still be in "MissingFont".
# Font substitution will take place when we render the document.
self.assertEqual("MissingFont", doc.first_section.body.first_paragraph.runs[0].font.name)

doc.save(ARTIFACTS_DIR + "FontSettings.resolve_fonts_before_loading_document.pdf")
```

Shows how to apply font substitution settings while loading a document.

```python
# Create a FontSettings object that will substitute the "Times New Roman" font
# with the font "Arvo" from our "MyFonts" folder.
font_settings = aw.fonts.FontSettings()
font_settings.set_fonts_folder(FONTS_DIR, False)
font_settings.substitution_settings.table_substitution.add_substitutes("Times New Roman", "Arvo")

# Set that FontSettings object as a property of a newly created LoadOptions object.
load_options = aw.loading.LoadOptions()
load_options.font_settings = font_settings

# Load the document, then render it as a PDF with the font substitution.
doc = aw.Document(MY_DIR + "Document.docx", load_options)

doc.save(ARTIFACTS_DIR + "LoadOptions.font_settings.pdf")
```

### See Also

* module [aspose.words.loading](../../)
* class [LoadOptions](../)

