﻿---
title: request_dictionary method
second_title: Aspose.Words for Python via .NET API Reference
description: "Notifies application that hyphenation dictionary for the specified language wasn't found and may need to be registered."
type: docs
weight: 10
url: /python-net/aspose.words/ihyphenationcallback/request_dictionary/
---

## request_dictionary(language) {#str}

Notifies application that hyphenation dictionary for the specified language wasn't found and may need to be registered.


Implementation should find a dictionary and register it using[Hyphenation.register_dictionary()](../../hyphenation/register_dictionary/#str_bytesio) methods.


If dictionary is unavailable for the specified language implementation can opt out of further calls for the same language
using[Hyphenation.register_dictionary()](../../hyphenation/register_dictionary/#str_str) with null value.



```python
def request_dictionary(self, language: str):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| language | str |  |

Exceptions thrown by this method will abort execution of page layout process.


### See Also

* module [aspose.words](../../)
* class [IHyphenationCallback](../)

