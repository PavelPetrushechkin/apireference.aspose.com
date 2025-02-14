---
title: CreateFilterRule
second_title: Aspose.GIS für .NET-API-Referenz
description: Erstellt eine neue Regel die einen Symbolisierer auf das Feature anwendet wenn es den Filter passiert.
type: docs
weight: 20
url: /de/net/aspose.gis.rendering.symbolizers/rule/createfilterrule/
---
## Rule.CreateFilterRule method

Erstellt eine neue Regel, die einen Symbolisierer auf das Feature anwendet, wenn es den Filter passiert.

```csharp
public static Rule CreateFilterRule(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filter | Func`2 | Legt fest, wann der Symbolizer verwendet werden soll. |
| symbolizer | VectorSymbolizer | Symbolisierer zum Anwenden. |

### Rückgabewert

Neues Regelobjekt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Filter ist`null`. |

### Siehe auch

* class [Feature](../../../aspose.gis/feature)
* class [VectorSymbolizer](../../vectorsymbolizer)
* class [Rule](../../rule)
* namensraum [Aspose.Gis.Rendering.Symbolizers](../../rule)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
