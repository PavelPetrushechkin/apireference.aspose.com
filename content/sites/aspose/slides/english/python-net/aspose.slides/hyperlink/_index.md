---
title: Hyperlink
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 740
url: /python-net/aspose.slides/hyperlink/
---

## Hyperlink class

Represents a hyperlink.

The Hyperlink type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Hyperlink(url)|Initializes a new instance of the Hyperlink class|
|Hyperlink(slide)|Initializes a new instance of the Hyperlink class|
|Hyperlink(source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)|Initializes a new instance of the Hyperlink class|
## Properties
| Name | Description |
| :- | :- |
|as_i_presentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/slides/python-net/aspose.slides/ipresentationcomponent/).|
|no_action|Returns a special "do nothing" hyperlink.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|media|Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|next_slide|Returns a hyperlink to the next slide.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|previous_slide|Returns a hyperlink to the previous slide.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|first_slide|Returns a hyperlink to the first slide of the presentation.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|last_slide|Returns a hyperlink to the last slide of the presentation.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|last_vieved_slide|Returns a hyperlink to the last viewed slide.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|end_show|Returns a hyperlink which ends the show.<br/>            Read-only [Hyperlink](/slides/python-net/aspose.slides/hyperlink/).|
|action_type|Returns type of Hyperlink's action.<br/>            Read-only [HyperlinkActionType](/slides/python-net/aspose.slides/hyperlinkactiontype/).|
|external_url|Specifies the external URL.<br/>            Read-only string.|
|target_slide|If the Hyperlink targets specific slide returns this slide.<br/>            Read-only [ISlide](/slides/python-net/aspose.slides/islide/).|
|target_frame|Returns the frame within the parent HTML frameset for the target<br/>            of the parent hyperlink when one exists.<br/>            Read/wite string.|
|tooltip|Returns the string which may be surfaced in a user interface<br/>            as associated with the parent hyperlink.<br/>            Read/write string.|
|history|Determines whether the target of the parent hyperlink shall be added<br/>            to a list of viewed hyperlinks when it is invoked.<br/>            Read/write bool.|
|highlight_click|Determines whether the hyperlink should be highlighted on click.<br/>            Read/write bool.|
|stop_sound_on_click|Determines whether the sound should be stopped on hyperlink click.<br/>            Read/write bool.|
|color_source|Represents the source of hyperlink color - either styles or portion format.<br/>            Read/write [HyperlinkColorSource](/slides/python-net/aspose.slides/hyperlinkcolorsource/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/slides/python-net/aspose.slides/ibaseslide/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/slides/python-net/aspose.slides/ipresentation/).|
## Methods
| Name | Description |
| :- | :- |
|equals(hlink)|Determines whether the two Hyperlink instances are equal.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

