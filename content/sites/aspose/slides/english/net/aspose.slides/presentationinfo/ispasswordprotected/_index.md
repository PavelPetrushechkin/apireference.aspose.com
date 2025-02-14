---
title: IsPasswordProtected
second_title: Aspose.Sildes for .NET API Reference
description: Gets a value that indicates whether a binded presentation is protected by a password to open.
type: docs
weight: 20
url: /net/aspose.slides/presentationinfo/ispasswordprotected/
---
## PresentationInfo.IsPasswordProtected property

Gets a value that indicates whether a binded presentation is protected by a password to open.

```csharp
public bool IsPasswordProtected { get; }
```

### Examples

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsPasswordProtected)
{
    Console.WriteLine("The presentation '" + presentationFilePath + "' is protected by password to open.");
}
```

### See Also

* class [PresentationInfo](../../presentationinfo)
* namespace [Aspose.Slides](../../presentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
