---
title: PdfDevice
second_title: Aspose.TeX for .NET API Reference
description: Implements the interface for outputting text and graphic content to PDF document.
type: docs
weight: 350
url: /net/aspose.tex.presentation.pdf/pdfdevice/
---
## PdfDevice class

Implements the interface for outputting text and graphic content to PDF document.

```csharp
public class PdfDevice : Device, IFragmentRasterizer, IInteractiveDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfDevice](pdfdevice#constructor)() | Creates new instance. The output file will be written to the output working directory taking the job name as a file name. |
| [PdfDevice](pdfdevice#constructor_1)(Stream) | Creates new instance. The output file will be written to specified stream. |

## Properties

| Name | Description |
| --- | --- |
| override [DestinationName](../../aspose.tex.presentation.pdf/pdfdevice/destinationname) { get; } | Gets destination name: output file name or device description. |
| override [Fill](../../aspose.tex.presentation.pdf/pdfdevice/fill) { get; set; } | Gets/sets the current fill. |
| override [FillOpacity](../../aspose.tex.presentation.pdf/pdfdevice/fillopacity) { get; set; } | Gets/sets the current fill opacity. |
| override [IsReady](../../aspose.tex.presentation.pdf/pdfdevice/isready) { get; } | Shows if device is ready for output. |
| override [PageCount](../../aspose.tex.presentation.pdf/pdfdevice/pagecount) { get; } | Gets the number of pages. |
| override [Stroke](../../aspose.tex.presentation.pdf/pdfdevice/stroke) { get; set; } | Gets/sets the current stroke. |
| override [StrokeOpacity](../../aspose.tex.presentation.pdf/pdfdevice/strokeopacity) { get; set; } | Gets/sets the current stroke opacity. |

## Methods

| Name | Description |
| --- | --- |
| [AddBookmark](../../aspose.tex.presentation.pdf/pdfdevice/addbookmark)(string, PointF) | Adds the bookmark identified by the name. |
| override [AddHyperlink](../../aspose.tex.presentation.pdf/pdfdevice/addhyperlink)(RectangleF, Pen, string) | Set the hyperlink with a URI as its target. |
| override [Create](../../aspose.tex.presentation.pdf/pdfdevice/create)() | Creates a copy of this device. |
| override [Dispose](../../aspose.tex.presentation.pdf/pdfdevice/dispose)() | Disposes this device instance. Finalizes this device instance graphics state, i.e. switches APS composing context to the ApsCanvas of the level higher then this device's graphics state ApsCanvas. |
| override [DrawPath](../../aspose.tex.presentation.pdf/pdfdevice/drawpath)(GraphicsPath) | Draws a path. |
| override [DrawString](../../aspose.tex.presentation.pdf/pdfdevice/drawstring)(string, float, float, List&lt;GlyphData&gt;) | Draws a text string. |
| override [EndDocument](../../aspose.tex.presentation.pdf/pdfdevice/enddocument)() | Finalizes the whole document. |
| [EndFragment](../../aspose.tex.presentation.pdf/pdfdevice/endfragment)() | Ends a fragment to rasterize. |
| override [EndPage](../../aspose.tex.presentation.pdf/pdfdevice/endpage)() | Finalizes a page. |
| override [FillPath](../../aspose.tex.presentation.pdf/pdfdevice/fillpath)(GraphicsPath) | Fill a path. |
| override [Init](../../aspose.tex.presentation.pdf/pdfdevice/init)() | Initializes device. |
| override [SetClip](../../aspose.tex.presentation.pdf/pdfdevice/setclip)(GraphicsPath) | Sets the current clip path. |
| override [SetTransform](../../aspose.tex.presentation.pdf/pdfdevice/settransform)(Matrix) | Sets the current coordinate space transformation. |
| override [ShowImage](../../aspose.tex.presentation.pdf/pdfdevice/showimage)(PointF, SizeF, byte[]) | Shows a raster image. |
| override [StartDocument](../../aspose.tex.presentation.pdf/pdfdevice/startdocument)() | Starts the whole document. |
| [StartFragment](../../aspose.tex.presentation.pdf/pdfdevice/startfragment)() | Starts a fragment to rasterize. |
| override [StartPage](../../aspose.tex.presentation.pdf/pdfdevice/startpage)(float, float) | Starts a new page. |

### See Also

* class [Device](../../aspose.tex.presentation/device)
* interface [IFragmentRasterizer](../../aspose.tex.presentation/ifragmentrasterizer)
* interface [IInteractiveDevice](../../aspose.tex.presentation/iinteractivedevice)
* namespace [Aspose.TeX.Presentation.Pdf](../../aspose.tex.presentation.pdf)
* assembly [Aspose.TeX](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.TeX.dll -->
