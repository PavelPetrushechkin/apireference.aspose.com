---
title: TiffImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7890
url: /net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

The tiff image.

```csharp
public sealed class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffImage](tiffimage)(TiffFrame) | Initializes a new instance of the [`TiffImage`](../tiffimage) class. |
| [TiffImage](tiffimage)(TiffFrame[]) | Initializes a new instance of the [`TiffImage`](../tiffimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe) { get; set; } | Gets or sets the active frame. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder) { get; set; } | Gets or sets a value indicating the tiff byte order. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffimage/exifdata) { get; set; } | Gets or sets EXIF data for the active frame. |
| override [FileFormat](../../aspose.imaging.fileformats.tiff/tiffimage/fileformat) { get; } | Gets a value of file format |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames) { get; } | Gets Frames array of the image. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha) { get; } | Gets the Has alpha channel. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Gets the image height. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution) { get; set; } | Gets the horizontal resolution, in pixels per inch, of this [`Image`](../../aspose.imaging/image). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount) { get; } | Gets the page count. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages) { get; } | Gets the pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents) { get; set; } | Gets or sets a value indicating whether components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution) { get; set; } | Gets the vertical resolution, in pixels per inch, of this [`Image`](../../aspose.imaging/image). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Gets the image width. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Gets or sets XMP data from frame. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add)(TiffImage) | Adds the specified image's frames to current frame. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe)(TiffFrame) | Adds the frame to image |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes)(TiffFrame[]) | Adds the frames array to image |
| [AddPage](../../aspose.imaging.fileformats.tiff/tiffimage/addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma)(float, float, float) | Gamma-correction of an image. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions)() | Helper method to make horizontal and vertical resolutions equal. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop)(Rectangle) | Cropping the image. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Gets an image pixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale)() | Transformation of an image to its grayscale representation |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe)(int, TiffFrame) | The insert frame. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Loads 32-bit ARGB pixels. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Loads 64-bit ARGB pixels. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Loads pixels in CMYK format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Loads 32-bit ARGB pixels partially by packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Loads pixels partially by packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Loads pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) and [`Rotate`](../../aspose.imaging/rasterimage/rotate) methods. |
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) and [`Rotate`](./rotate) methods. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe)(int) | Removes the frame by its index. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe)(TiffFrame) | Removes the specified frame. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe)(int, TiffFrame) | Replaces the frame at the specified position. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate)(float, bool, Color) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converts raster image to the bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

### Examples

Create Graphics Path from Path Resources in TIFF image.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Create the GraphicsPath using PathResources from TIFF image
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Draw red line and save the image
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Create Path Resources using Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Create rectangular Figure for GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Create GraphicsPath using our Figure
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Set PathResources using GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Save the image
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
