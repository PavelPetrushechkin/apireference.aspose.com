﻿---
title: FileFontSource constructor
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.fonts.FileFontSource constructor"
type: docs
weight: 10
url: /python-net/aspose.words.fonts/filefontsource/__init__/
---

## FileFontSource(file_path) {#str}

Ctor.


```python
def __init__(self, file_path: str):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| file_path | str |  |

## FileFontSource(file_path, priority) {#str_int}

Ctor.


```python
def __init__(self, file_path: str, priority: int):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| file_path | str |  |
| priority | int |  |

## FileFontSource(file_path, priority, cache_key) {#str_int_str}

Ctor.


```python
def __init__(self, file_path: str, priority: int, cache_key: str):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| file_path | str |  |
| priority | int |  |
| cache_key | str |  |

## Examples

Shows how to use a font file in the local file system as a font source.

```python
file_font_source = aw.fonts.FileFontSource(MY_DIR + "Alte DIN 1451 Mittelschrift.ttf", 0)

doc = aw.Document()
doc.font_settings = aw.fonts.FontSettings()
doc.font_settings.set_fonts_sources([file_font_source])

self.assertEqual(MY_DIR + "Alte DIN 1451 Mittelschrift.ttf", file_font_source.file_path)
self.assertEqual(aw.fonts.FontSourceType.FONT_FILE, file_font_source.type)
self.assertEqual(0, file_font_source.priority)
```

## See Also

* module [aspose.words.fonts](../../)
* class [FileFontSource](../)

