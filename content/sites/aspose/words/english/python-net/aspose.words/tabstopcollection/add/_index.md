﻿---
title: add method
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.TabStopCollection.add method"
type: docs
weight: 30
url: /python-net/aspose.words/tabstopcollection/add/
---

## add(tab_stop) {#tabstop}

Adds or replaces a tab stop in the collection.


```python
def add(self, tab_stop: aspose.words.TabStop):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| tab_stop | [TabStop](../../tabstop/) |  |

If a tab stop already exists at the specified position, it is replaced.




## add(position, alignment, leader) {#float_tabalignment_tableader}

Adds or replaces a tab stop in the collection.


```python
def add(self, position: float, alignment: aspose.words.TabAlignment, leader: aspose.words.TabLeader):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| position | float |  |
| alignment | [TabAlignment](../../tabalignment/) |  |
| leader | [TabLeader](../../tableader/) |  |

If a tab stop already exists at the specified position, it is replaced.




## Examples

Shows how to add custom tab stops to a document.

```python
doc = aw.Document()
paragraph = doc.get_child(aw.NodeType.PARAGRAPH, 0, True).as_paragraph()

# Below are two ways of adding tab stops to a paragraph's collection of tab stops via the "paragraph_format" property.
# 1 -  Create a "TabStop" object, and then add it to the collection:
tab_stop = aw.TabStop(aw.ConvertUtil.inch_to_point(3), aw.TabAlignment.LEFT, aw.TabLeader.DASHES)
paragraph.paragraph_format.tab_stops.add(tab_stop)

# 2 -  Pass the values for properties of a new tab stop to the "add" method:
paragraph.paragraph_format.tab_stops.add(aw.ConvertUtil.millimeter_to_point(100),
                                         aw.TabAlignment.LEFT, aw.TabLeader.DASHES)

# Add tab stops at 5 cm to all paragraphs.
for para in doc.get_child_nodes(aw.NodeType.PARAGRAPH, True):
    para = para.as_paragraph()
    para.paragraph_format.tab_stops.add(aw.ConvertUtil.millimeter_to_point(50),
                                        aw.TabAlignment.LEFT, aw.TabLeader.DASHES)

# Every "tab" character takes the builder's cursor to the location of the next tab stop.
builder = aw.DocumentBuilder(doc)
builder.writeln("Start\tTab 1\tTab 2\tTab 3\tTab 4")

doc.save(ARTIFACTS_DIR + "TabStopCollection.add_tab_stops.docx")
```

## See Also

* module [aspose.words](../../)
* class [TabStopCollection](../)

