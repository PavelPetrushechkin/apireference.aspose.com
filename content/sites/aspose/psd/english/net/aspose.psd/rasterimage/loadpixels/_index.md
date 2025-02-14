---
title: LoadPixels
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 400
url: /net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Loads pixels.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to load pixels from. |

## Return Value

The loaded pixels array.

### Examples

This example shows how to Loads Pixel information in an Array of Type Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in PSD format) using MemoryStream object.

```csharp
[C#]

//Create an instance of MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Create an instance of PsdOptions and set its various properties including the Source property
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Create an instance of Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Get the pixels of image by specifying the area as image boundary
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over the Array and sets color of alrenative indexed pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Set the indexed pixel color to yellow
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Set the indexed pixel color to blue
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Apply the pixel changes to the image
        image.SavePixels(image.Bounds, pixels);

        // save all changes.
        image.Save();
    }

    //Write MemoryStream to File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### See Also

* struct [Color](../../color)
* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* namespace [Aspose.PSD](../../rasterimage)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
