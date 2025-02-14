---
title: Paragraph
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 3270
url: /python-net/aspose.slides/paragraph/
---

## Paragraph class

Represents a paragraph of text.

The Paragraph type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Paragraph()|Initializes a new instance of the Paragraph class with default properties.|
|Paragraph(para)|Initializes a new instance of the Paragraph class|
## Properties
| Name | Description |
| :- | :- |
|portions|Returns the collection of a text portions.<br/>            Read-only [IPortionCollection](/slides/python-net/aspose.slides/iportioncollection/).|
|paragraph_format|Returns the formatting object for this paragraph.<br/>            Read-only [IParagraphFormat](/slides/python-net/aspose.slides/iparagraphformat/).|
|text|Gets or sets the the plain text of a paragraph.<br/>            Read/write string.|
|end_paragraph_portion_format|Specifies the portion properties that are to be used if another portion is inserted after <br/>            the last one.|
|as_i_slide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/slides/python-net/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/slides/python-net/aspose.slides/ibaseslide/).|
|as_i_presentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/slides/python-net/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/slides/python-net/aspose.slides/ipresentation/).|
## Methods
| Name | Description |
| :- | :- |
|join_portions_with_same_formatting()|Joins runs with same formatting.|
|get_rect()|Get coordinates of rect that bounds paragraph. The rect includes all the lines of<br/>            text in paragraph, including empty ones.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

