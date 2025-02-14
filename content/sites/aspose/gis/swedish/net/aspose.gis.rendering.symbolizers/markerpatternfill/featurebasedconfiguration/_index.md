---
title: FeatureBasedConfiguration
second_title: Aspose.GIS för .NET API Referens
description: En återuppringning som används för att konfigurera denna symboliserare innan en funktion renderas.
type: docs
weight: 20
url: /sv/net/aspose.gis.rendering.symbolizers/markerpatternfill/featurebasedconfiguration/
---
## MarkerPatternFill.FeatureBasedConfiguration property

En återuppringning som används för att konfigurera denna symboliserare innan en funktion renderas.

```csharp
public Action<Feature, MarkerPatternFill> FeatureBasedConfiguration { get; set; }
```

### Anmärkningar

Denna återuppringning anropas innan varje funktion renderas. Den accepterar en funktion som är på väg att renderas och en klon av denna symboliserare. Genom att ändra egenskaper för klonen är det möjligt att uppdatera symbolizers beteende baserat på egenskapens attribut.

### Se även

* class [Feature](../../../aspose.gis/feature)
* class [MarkerPatternFill](../../markerpatternfill)
* namnutrymme [Aspose.Gis.Rendering.Symbolizers](../../markerpatternfill)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
