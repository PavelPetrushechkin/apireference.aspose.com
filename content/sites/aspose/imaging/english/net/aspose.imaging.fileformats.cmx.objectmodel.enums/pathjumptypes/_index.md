---
title: PathJumpTypes
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 2080
url: /net/aspose.imaging.fileformats.cmx.objectmodel.enums/pathjumptypes/
---
## PathJumpTypes enumeration

Types of transitions between points of the [`CmxPathSpec`](../../aspose.imaging.fileformats.cmx.objectmodel.specs/cmxpathspec)

```csharp
public enum PathJumpTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MoveTo | `0` | The point is not connected to the previous one. Uses for visible points. |
| LineTo | `1` | The point is connected to the previous one through a straight line. Uses for visible points. |
| BezierTo | `2` | The point is connected to the previous visible point through a bi-cubic bezier curve. Uses for visible points. |
| BezierSupport | `3` | Uses for invisible auxiliary point to build a bi-cubic bezier curve. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Cmx.ObjectModel.Enums](../../aspose.imaging.fileformats.cmx.objectmodel.enums)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
