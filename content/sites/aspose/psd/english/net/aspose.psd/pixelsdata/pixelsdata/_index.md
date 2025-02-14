---
title: PixelsData
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.psd/pixelsdata/pixelsdata/
---
## PixelsData constructor (1 of 2)

Initializes a new instance of the [`PixelsData`](../../pixelsdata) class.

```csharp
public PixelsData()
```

### Examples

The following code shows you how to create a custom smart filter that has a custom renderer.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Inits the unsupported 'Crystallize' smart filter at input array
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // the 'Crystallize' smart filter ID.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Apply filter to SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Apply filter to layer mask
        smartFilter.ApplyToMask(maskLayer);

        //Apply filter to layer
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // the 'Crystallize' smart filter ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // get filter structure
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // get value of Crystallize Size
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### See Also

* class [PixelsData](../../pixelsdata)
* namespace [Aspose.PSD](../../pixelsdata)
* assembly [Aspose.PSD](../../../)

---

## PixelsData constructor (2 of 2)

Initializes a new instance of the [`PixelsData`](../../pixelsdata) class.

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The pixels data. |
| bounds | Rectangle | The pixels bounds rectangle. |

### Examples

The following code shows you how to create a custom smart filter that has a custom renderer.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Inits the unsupported 'Crystallize' smart filter at input array
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // the 'Crystallize' smart filter ID.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Apply filter to SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Apply filter to layer mask
        smartFilter.ApplyToMask(maskLayer);

        //Apply filter to layer
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // the 'Crystallize' smart filter ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // get filter structure
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // get value of Crystallize Size
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### See Also

* struct [Rectangle](../../rectangle)
* class [PixelsData](../../pixelsdata)
* namespace [Aspose.PSD](../../pixelsdata)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
