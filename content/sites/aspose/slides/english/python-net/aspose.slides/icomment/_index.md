---
title: IComment
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 1130
url: /python-net/aspose.slides/icomment/
---

## IComment class

Represents a comment on a slide.

The IComment type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|text|Returns or sets the plain text of a slide comment.<br/>            Read/write string.|
|created_time|Returns or sets the time of a comment creation.<br/>            Setting this property to min date value means no comment time is set.<br/>            Read/write datetime.|
|slide|Returns or sets the parent slide of a comment.<br/>            Read-only [ISlide](/slides/python-net/aspose.slides/islide/).|
|author|Returns the author of a comment.<br/>            Read-only [ICommentAuthor](/slides/python-net/aspose.slides/icommentauthor/).|
|position|Returns or sets the position of a comment on a slide.<br/>            Read/write aspose.pydrawing.PointF.|
|parent_comment|Gets or sets parent comment.<br/>            Read/write [IComment](/slides/python-net/aspose.slides/icomment/).|
## Methods
| Name | Description |
| :- | :- |
|remove()|Removes comment and all its replies from the parent collection.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

