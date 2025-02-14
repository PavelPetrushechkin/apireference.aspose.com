﻿---
title: compliance property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies the PDF standards compliance level for output documents."
type: docs
weight: 30
url: /python-net/aspose.words.saving/pdfsaveoptions/compliance/
---

## PdfSaveOptions.compliance property

Specifies the PDF standards compliance level for output documents.

Default is [PdfCompliance.PDF17](../../pdfcompliance/#PDF17).




### Examples

Shows how to set the PDF standards compliance level of saved PDF documents.

```python
doc = aw.Document(MY_DIR + "Images.docx")

# Create a "PdfSaveOptions" object that we can pass to the document's "save" method
# to modify how that method converts the document to .PDF.
save_options = aw.saving.PdfSaveOptions()

# Set the "compliance" property to "PdfCompliance.PDF_A1B" to comply with the "PDF/A-1b" standard,
# which aims to preserve the visual appearance of the document as Aspose.Words convert it to PDF.
# Set the "compliance" property to "PdfCompliance.PDF17" to comply with the "1.7" standard.
# Set the "compliance" property to "PdfCompliance.PDF_A1A" to comply with the "PDF/A-1a" standard,
# which complies with "PDF/A-1b" as well as preserving the document structure of the original document.
# This helps with making documents searchable but may significantly increase the size of already large documents.
save_options.compliance = pdf_compliance

doc.save(ARTIFACTS_DIR + "PdfSaveOptions.compliance.pdf", save_options)
```

### See Also

* module [aspose.words.saving](../../)
* class [PdfSaveOptions](../)

