---
title: Open
second_title: Aspose.GIS för .NET API Referens
description: Öppnar dettaAbstractPathsom en fil.
type: docs
weight: 120
url: /sv/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

Öppnar detta`AbstractPath`som en fil.

```csharp
public abstract Stream Open(FileAccess access)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| access | FileAccess | Anger en delmängd av operationer som kan utföras på enStream. |

### Returvärde

AStream öppnas med angivetFileAccess .

### Anmärkningar

Om*access* har flagganWrite set, och filen finns inte, måste en arvtagare skapa den. An`AbstractPath` kan öppnas flera gånger av`Aspose.GIS` . Detta krävs för att kunna läsa en file oberoende med flera strömmar. Du ska inte cacha resultatet utan snarare returnera nyttStream varje gång kallas denna metod.

### Se även

* class [AbstractPath](../../abstractpath)
* namnutrymme [Aspose.Gis](../../abstractpath)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
