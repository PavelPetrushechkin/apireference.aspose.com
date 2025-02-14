---
title: License
second_title: Aspose.SVG för .NET API Referens
description: Tillhandahåller metoder för att licensiera komponenten.
type: docs
weight: 2160
url: /sv/net/aspose.svg/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [License](license)() | Initierar en ny instans av den här klassen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense_1)(string) | Licensierar komponenten. |

### Exempel

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller  komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för postsammansättningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

komponentjarfilen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* namnutrymme [Aspose.Svg](../../aspose.svg)
* hopsättning [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
