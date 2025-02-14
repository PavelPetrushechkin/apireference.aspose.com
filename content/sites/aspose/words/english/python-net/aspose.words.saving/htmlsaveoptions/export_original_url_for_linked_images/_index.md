﻿---
title: export_original_url_for_linked_images property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies whether original URL should be used as the URL of the linked images"
type: docs
weight: 210
url: /python-net/aspose.words.saving/htmlsaveoptions/export_original_url_for_linked_images/
---

## HtmlSaveOptions.export_original_url_for_linked_images property

Specifies whether original URL should be used as the URL of the linked images.
Default value is ``false``.


If value is set to ``true``[ImageData.source_full_name](../../../aspose.words.drawing/imagedata/source_full_name/) value is used
as the URL of linked images and linked images are not loaded into document's folder
or [HtmlSaveOptions.images_folder](../images_folder/).

If value is set to ``false`` linked images are loaded into document's folder
or [HtmlSaveOptions.images_folder](../images_folder/) and URL of each linked image is constructed depending
on document's folder, [HtmlSaveOptions.images_folder](../images_folder/) 
and [HtmlSaveOptions.images_folder_alias](../images_folder_alias/) properties.




### Examples

Shows how to set folders and folder aliases for externally saved resources that Aspose.Words will create when saving a document to HTML.

```python
doc = aw.Document(MY_DIR + "Rendering.docx")

options = aw.saving.HtmlSaveOptions()
options.css_style_sheet_type = aw.saving.CssStyleSheetType.EXTERNAL
options.export_font_resources = True
options.image_resolution = 72
options.font_resources_subsetting_size_threshold = 0
options.fonts_folder = ARTIFACTS_DIR + "Fonts"
options.images_folder = ARTIFACTS_DIR + "Images"
options.resource_folder = ARTIFACTS_DIR + "Resources"
options.fonts_folder_alias = "http://example.com/fonts"
options.images_folder_alias = "http://example.com/images"
options.resource_folder_alias = "http://example.com/resources"
options.export_original_url_for_linked_images = True

doc.save(ARTIFACTS_DIR + "HtmlSaveOptions.folder_alias.html", options)
```

### See Also

* module [aspose.words.saving](../../)
* class [HtmlSaveOptions](../)

