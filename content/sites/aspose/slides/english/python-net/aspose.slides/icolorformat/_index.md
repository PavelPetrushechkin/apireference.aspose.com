---
title: IColorFormat
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 1060
url: /python-net/aspose.slides/icolorformat/
---

## IColorFormat class

Represents a color used in a presentation.

The IColorFormat type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|color_type|Returns or sets the color definition method.<br/>            Read/write [ColorType](/slides/python-net/aspose.slides/colortype/).|
|color|Returns resulting color (with all color transformations applied).<br/>            Sets RGB colors and clears all color transformations.<br/>            Read/write aspose.pydrawing.Color.|
|preset_color|Returns or sets the color preset.<br/>            Read/write [PresetColor](/slides/python-net/aspose.slides/presetcolor/).|
|system_color|Returns or sets the color identified by the system color table.<br/>            Read/write [SystemColor](/slides/python-net/aspose.slides/systemcolor/).|
|scheme_color|Returns or sets the color identified by a color scheme.<br/>            Read/write [SchemeColor](/slides/python-net/aspose.slides/schemecolor/).|
|r|Returns or sets the red component of a color. All color transformations are ignored.<br/>            Read/write int.|
|g|Returns or sets the green component of a color. All color transformations are ignored.<br/>            Read/write int.|
|b|Returns or sets the blue component of a color. All color transformations are ignored.<br/>            Read/write int.|
|float_r|Returns or sets the red component of a color. All color transformations are ignored.<br/>            Read/write|
|float_g|Returns or sets the green component of a color. All color transformations are ignored.<br/>            Read/write|
|float_b|Returns or sets the blue component of a color. All color transformations are ignored.<br/>            Read/write|
|hue|Returns or sets the hue component of a color in HSL representation.<br/>            All color transformations are ignored.<br/>            Read/write|
|saturation|Returns or sets the saturation component of a color in HSL representation.<br/>            All color transformations are ignored.<br/>            Read/write|
|luminance|Returns or sets the luminance component of a color in HSL representation.<br/>            All color transformations are ignored.<br/>            Read/write|
|color_transform|Returns the collection of color transformations applied to a color.<br/>            Read-only [IColorOperationCollection](/slides/python-net/aspose.slides/icoloroperationcollection/).|
|as_i_fill_param_source|Returns IFillParamSource interface.<br/>            Read-only [IFillParamSource](/slides/python-net/aspose.slides/ifillparamsource/).|
## Methods
| Name | Description |
| :- | :- |
|to_string(format)|Returns a string that represents the current color format.|
|copy_from(color)|Copy color format from "color".|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

