---
title: ImageRefTypeEnum
second_title: Aspose.Finance for .NET API Reference
description: Image reference type enum.
type: docs
weight: 2310
url: /net/aspose.finance.ofx/imagereftypeenum/
---
## ImageRefTypeEnum enumeration

Image reference type enum.

```csharp
public enum ImageRefTypeEnum
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| OPAQUE | `0` | The image is accessed via an explicit OFX [`ImageRequest`](../../aspose.finance.ofx.image/imagerequest) request, which will be followed by the image data. |
| URL | `1` | The image is accessed directly via the URL provided. The image cannot be retrieved via an OFX image request. The expectation is that the client will not provide authentication and will simply follow the URL provided. |
| FORMURL | `2` | The image is accessed directly via an encoded URL. The image cannot be retrieved via an OFX image request. The expectation is that the client will send authentication to the server. |

### See Also

* namespace [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* assembly [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
