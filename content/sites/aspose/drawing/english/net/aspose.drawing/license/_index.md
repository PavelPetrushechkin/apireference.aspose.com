---
title: License
second_title: Aspose.Drawing for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.drawing/license/
---
## License class

Provides methods to license the component.

```csharp
public class License
```

## Constructors

| Name | Description |
| --- | --- |
| [License](license)() | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [SetLicense](../../aspose.drawing/license/setlicense)(Stream) | Licenses the component. |
| [SetLicense](../../aspose.drawing/license/setlicense)(string) | Licenses the component. |

### Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains  the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");

```

### See Also

* namespace [Aspose.Drawing](../../aspose.drawing)
* assembly [Aspose.Drawing](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Drawing.dll -->
