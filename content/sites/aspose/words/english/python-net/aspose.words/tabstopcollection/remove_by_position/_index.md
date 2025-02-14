﻿---
title: remove_by_position method
second_title: Aspose.Words for Python via .NET API Reference
description: "Removes a tab stop at the specified position from the collection."
type: docs
weight: 110
url: /python-net/aspose.words/tabstopcollection/remove_by_position/
---

## remove_by_position(position) {#float}

Removes a tab stop at the specified position from the collection.


```python
def remove_by_position(self, position: float):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| position | float |  |

### Examples

Shows how to modify the position of the right tab stop in TOC related paragraphs.

```python
doc = aw.Document(MY_DIR + "Table of contents.docx")

# Iterate through all paragraphs with TOC result-based styles; this is any style between TOC and TOC9.
for para in doc.get_child_nodes(aw.NodeType.PARAGRAPH, True):
    para = para.as_paragraph()
    if (para.paragraph_format.style.style_identifier >= aw.StyleIdentifier.TOC1 and
        para.paragraph_format.style.style_identifier <= aw.StyleIdentifier.TOC9):

        # Get the first tab used in this paragraph, this should be the tab used to align the page numbers.
        tab = para.paragraph_format.tab_stops[0]

        # Replace the first default tab, stop with a custom tab stop.
        para.paragraph_format.tab_stops.remove_by_position(tab.position)
        para.paragraph_format.tab_stops.add(tab.position - 50, tab.alignment, tab.leader)

doc.save(ARTIFACTS_DIR + "Styles.change_tocs_tab_stops.docx")
```

### See Also

* module [aspose.words](../../)
* class [TabStopCollection](../)

