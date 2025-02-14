---
title: CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: This field can contain saving strategy that must be used if present during conversion for customized handling of created referenced external images files like embedded BMP or JPEG embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converters code itself not in custom code please set in custom code flag CustomProcessingCancelled of imageSavingInfo parameters variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
type: docs
weight: 30
url: /net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced external images files (like embedded BMP or JPEG) embedded into saved SVG. That strategy must process resources and return string that represents desirable URI of saved resource in generated SVG. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### See Also

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy)
* class [SvgSaveOptions](../../svgsaveoptions)
* namespace [Aspose.Pdf](../../svgsaveoptions)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
