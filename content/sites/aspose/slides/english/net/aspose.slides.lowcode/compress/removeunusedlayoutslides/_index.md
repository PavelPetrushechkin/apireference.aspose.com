---
title: RemoveUnusedLayoutSlides
second_title: Aspose.Sildes for .NET API Reference
description: Makes compression of the Presentationaspose.slides/presentation by removing unused layout slides.
type: docs
weight: 10
url: /net/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress.RemoveUnusedLayoutSlides method

Makes compression of the [`Presentation`](../../../aspose.slides/presentation) by removing unused layout slides.

```csharp
public static void RemoveUnusedLayoutSlides(Presentation pres)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pres | Presentation | The presentation instance |

### Examples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [Presentation](../../../aspose.slides/presentation)
* class [Compress](../../compress)
* namespace [Aspose.Slides.LowCode](../../compress)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
