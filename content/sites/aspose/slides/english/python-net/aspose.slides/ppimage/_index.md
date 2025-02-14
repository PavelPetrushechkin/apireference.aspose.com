---
title: PPImage
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 3250
url: /python-net/aspose.slides/ppimage/
---

## PPImage class

Represents an image in a presentation.

The PPImage type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|binary_data|Returns the copy of an image's data.<br/>            Read-only int[].|
|system_image|Returns the copy of an image.<br/>            Read-only aspose.pydrawing.Image.|
|svg_image|Returns or sets ISvgImage object [ISvgImage](/slides/python-net/aspose.slides/isvgimage/)|
|content_type|Returns a MIME type of an image, encoded in [binary_data](/slides/python-net/aspose.slides/ppimage/).<br/>            Read-only string.|
|width|Returns a width of an image.<br/>            Read-only|
|height|Returns a height of an image.<br/>            Read-only|
|x|Returns a X-offset of an image.<br/>            Read-only|
|y|Returns a Y-offset of an image.<br/>            Read-only|
## Methods
| Name | Description |
| :- | :- |
|replace_image(new_image_data)|Replaces image data.|
|replace_image(new_image)|Replaces image data. Attention: when Image is metafile - it will be rasterized due to restrictions of GDI+. Use ReplaceImage(byte[]) instead|
|replace_image(new_image)|Replaces image data.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

