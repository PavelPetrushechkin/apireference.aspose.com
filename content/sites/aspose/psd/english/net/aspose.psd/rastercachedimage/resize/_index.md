---
title: Resize
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 120
url: /net/aspose.psd/rastercachedimage/resize/
---
## RasterCachedImage.Resize method (1 of 2)

Resizes the image.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

### Examples

The following code demonstrates how to resize an image with a new SinC resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new Bell resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new Mitchell resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CatmullRom resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CubicBSpline resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CubicConvolution resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### See Also

* enum [ResizeType](../../resizetype)
* class [RasterCachedImage](../../rastercachedimage)
* namespace [Aspose.PSD](../../rastercachedimage)
* assembly [Aspose.PSD](../../../)

---

## RasterCachedImage.Resize method (2 of 2)

Resizes the image.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

### See Also

* class [ImageResizeSettings](../../imageresizesettings)
* class [RasterCachedImage](../../rastercachedimage)
* namespace [Aspose.PSD](../../rastercachedimage)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
