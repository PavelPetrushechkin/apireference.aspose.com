﻿---
title: max_characters_per_line property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets an integer value that specifies the maximum number of characters per one line"
type: docs
weight: 40
url: /python-net/aspose.words.saving/txtsaveoptions/max_characters_per_line/
---

## TxtSaveOptions.max_characters_per_line property

Gets or sets an integer value that specifies the maximum number of characters per one line.
The default value is 0, that means no limit.


### Examples

Shows how to set maximum number of characters per line.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.write("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. " +
              "Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.")

# Set 30 characters as maximum allowed per one line.
save_options = aw.saving.TxtSaveOptions()
save_options.max_characters_per_line = 30

doc.save(ARTIFACTS_DIR + "TxtSaveOptions.max_characters_per_line.txt", save_options)
```

### See Also

* module [aspose.words.saving](../../)
* class [TxtSaveOptions](../)

