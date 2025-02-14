﻿---
title: vertical_position property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets vertical distance between the edge of the frame and the item specified by the [FrameFormat.relative_vertical_position](../relative_vertical_position/) property."
type: docs
weight: 110
url: /python-net/aspose.words/frameformat/vertical_position/
---

## FrameFormat.vertical_position property

Gets vertical distance between the edge of the frame and the item specified by the [FrameFormat.relative_vertical_position](../relative_vertical_position/) property.



### Examples

Shows how to get information about formatting properties of paragraphs that are frames.

```python
doc = aw.Document(MY_DIR + "Paragraph frame.docx")

for paragraph in doc.first_section.body.paragraphs:
    paragraph = paragraph.as_paragraph()
    if paragraph.frame_format.is_frame:
        paragraph_frame = paragraph
        break

self.assertEqual(233.3, paragraph_frame.frame_format.width)
self.assertEqual(138.8, paragraph_frame.frame_format.height)
self.assertEqual(aw.HeightRule.AT_LEAST, paragraph_frame.frame_format.height_rule)
self.assertEqual(aw.drawing.HorizontalAlignment.DEFAULT, paragraph_frame.frame_format.horizontal_alignment)
self.assertEqual(aw.drawing.VerticalAlignment.DEFAULT, paragraph_frame.frame_format.vertical_alignment)
self.assertEqual(34.05, paragraph_frame.frame_format.horizontal_position)
self.assertEqual(aw.drawing.RelativeHorizontalPosition.PAGE, paragraph_frame.frame_format.relative_horizontal_position)
self.assertEqual(9.0, paragraph_frame.frame_format.horizontal_distance_from_text)
self.assertEqual(20.5, paragraph_frame.frame_format.vertical_position)
self.assertEqual(aw.drawing.RelativeVerticalPosition.PARAGRAPH, paragraph_frame.frame_format.relative_vertical_position)
self.assertEqual(0.0, paragraph_frame.frame_format.vertical_distance_from_text)
```

### See Also

* module [aspose.words](../../)
* class [FrameFormat](../)

