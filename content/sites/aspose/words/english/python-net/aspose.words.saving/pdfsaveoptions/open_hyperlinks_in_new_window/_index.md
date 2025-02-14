﻿---
title: open_hyperlinks_in_new_window property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets a value determining whether hyperlinks in the output Pdf document are forced to be opened in a new window (or tab) of a browser."
type: docs
weight: 200
url: /python-net/aspose.words.saving/pdfsaveoptions/open_hyperlinks_in_new_window/
---

## PdfSaveOptions.open_hyperlinks_in_new_window property

Gets or sets a value determining whether hyperlinks in the output Pdf document
are forced to be opened in a new window (or tab) of a browser.

The default value is ``false``. When this value is set to ``true``
hyperlinks are saved using JavaScript code.
JavaScript code is ``app.launchURL("URL", true);``,
where ``URL`` is a hyperlink.


Note that if this option is set to ``true`` hyperlinks can't work
in some PDF readers e.g. Chrome, Firefox.


JavaScript actions are prohibited by PDF/A-1 and PDF/A-2 compliance. ``false`` will be used automatically when
saving to PDF/A-1 and PDF/A-2.




### Examples

Shows how to save hyperlinks in a document we convert to PDF so that they open new pages when we click on them.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
builder.insert_hyperlink("Testlink", "https://www.google.com/search?q=%20aspose", False)

# Create a "PdfSaveOptions" object that we can pass to the document's "save" method
# to modify how that method converts the document to .PDF.
options = aw.saving.PdfSaveOptions()

# Set the "open_hyperlinks_in_new_window" property to "True" to save all hyperlinks using Javascript code
# that forces readers to open these links in new windows/browser tabs.
# Set the "open_hyperlinks_in_new_window" property to "False" to save all hyperlinks normally.
options.open_hyperlinks_in_new_window = open_hyperlinks_in_new_window

doc.save(ARTIFACTS_DIR + "PdfSaveOptions.open_hyperlinks_in_new_window.pdf", options)
```

### See Also

* module [aspose.words.saving](../../)
* class [PdfSaveOptions](../)

