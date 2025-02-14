---
title: XpsOptions
second_title: Aspose.Sildes for .NET API Reference
description: Provides options that control how a presentation is saved in XPS format.
type: docs
weight: 4320
url: /net/aspose.slides.export/xpsoptions/
---
## XpsOptions class

Provides options that control how a presentation is saved in XPS format.

```csharp
public class XpsOptions : SaveOptions, IXpsOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsOptions](xpsoptions)() | Default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returns or sets font used in case source font is not found. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/xpsoptions/drawslidesframe) { get; set; } | True to draw black frame around each slide. Read/write Boolean. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Represents a callback object for saving progress updates in percentage. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SaveMetafilesAsPng](../../aspose.slides.export/xpsoptions/savemetafilesaspng) { get; set; } | True to convert all metafiles used in a presentation to the PNG images. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/xpsoptions/showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### See Also

* class [SaveOptions](../saveoptions)
* interface [IXpsOptions](../ixpsoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
