---
title: License
second_title: Aspose.HTML for .NET API Reference
description: Provides methods to license the component.
type: docs
weight: 3800
url: /net/aspose.html/license/
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
| [SetLicense](../../aspose.html/license/setlicense#setlicense)(Stream) | Licenses the component. |
| [SetLicense](../../aspose.html/license/setlicense#setlicense_1)(string) | Licenses the component. |

### Examples

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

the component jar file:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### See Also

* namespace [Aspose.Html](../../aspose.html)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
