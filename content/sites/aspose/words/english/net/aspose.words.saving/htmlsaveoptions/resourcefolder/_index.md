---
title: ResourceFolder
second_title: Aspose.Words for .NET API Reference
description: Specifies a physical folder where all resources like images fonts and external CSS are saved when a document is exported to HTML. Default is an empty string.
type: docs
weight: 420
url: /net/aspose.words.saving/htmlsaveoptions/resourcefolder/
---
## HtmlSaveOptions.ResourceFolder property

Specifies a physical folder where all resources like images, fonts, and external CSS are saved when a document is exported to HTML. Default is an empty string.

```csharp
public string ResourceFolder { get; set; }
```

## Remarks

`ResourceFolder` is the simplest way to specify a folder where all resources should be written. Another way is to use individual properties [`FontsFolder`](../fontsfolder), [`ImagesFolder`](../imagesfolder), and [`CssStyleSheetFileName`](../cssstylesheetfilename).

`ResourceFolder` has a lower priority than folders specified via [`FontsFolder`](../fontsfolder), [`ImagesFolder`](../imagesfolder), and [`CssStyleSheetFileName`](../cssstylesheetfilename). For example, if both `ResourceFolder` and [`FontsFolder`](../fontsfolder) are specified, fonts will be saved to [`FontsFolder`](../fontsfolder), while images and CSS will be saved to `ResourceFolder`.

If the folder specified by `ResourceFolder` doesn't exist, it will be created automatically.

## Examples

Shows how to set folders and folder aliases for externally saved resources that Aspose.Words will create when saving a document to HTML.

```csharp
Document doc = new Document(MyDir + "Rendering.docx");

HtmlSaveOptions options = new HtmlSaveOptions
{
    CssStyleSheetType = CssStyleSheetType.External,
    ExportFontResources = true,
    ImageResolution = 72,
    FontResourcesSubsettingSizeThreshold = 0,
    FontsFolder = ArtifactsDir + "Fonts",
    ImagesFolder = ArtifactsDir + "Images",
    ResourceFolder = ArtifactsDir + "Resources",
    FontsFolderAlias = "http://example.com/fonts",
    ImagesFolderAlias = "http://example.com/images",
    ResourceFolderAlias = "http://example.com/resources",
    ExportOriginalUrlForLinkedImages = true
};

doc.Save(ArtifactsDir + "HtmlSaveOptions.FolderAlias.html", options);
```

### See Also

* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [Aspose.Words.Saving](../../htmlsaveoptions)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
