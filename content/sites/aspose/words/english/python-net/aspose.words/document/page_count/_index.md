﻿---
title: page_count property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets the number of pages in the document as calculated by the most recent page layout operation."
type: docs
weight: 300
url: /python-net/aspose.words/document/page_count/
---

## Document.page_count property

Gets the number of pages in the document as calculated by the most recent page layout operation.


### Examples

Shows how to count the number of pages in the document.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.write("Page 1")
builder.insert_break(aw.BreakType.PAGE_BREAK)
builder.write("Page 2")
builder.insert_break(aw.BreakType.PAGE_BREAK)
builder.write("Page 3")

# Verify the expected page count of the document.
self.assertEqual(3, doc.page_count)

# Getting the page_count property invoked the document's page layout to calculate the value.
# This operation will not need to be re-done when rendering the document to a fixed page save format,
# such as .pdf. So you can save some time, especially with more complex documents.
doc.save(ARTIFACTS_DIR + "Document.get_page_count.pdf")
```

### See Also

* module [aspose.words](../../)
* class [Document](../)
* method [Document.update_page_layout()](../update_page_layout/#default)

