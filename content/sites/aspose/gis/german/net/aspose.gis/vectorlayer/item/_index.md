---
title: Item
second_title: Aspose.GIS für .NET-API-Referenz
description: Ruft die abFeatureaspose.gis/feature am angegebenen Index.
type: docs
weight: 70
url: /de/net/aspose.gis/vectorlayer/item/
---
## VectorLayer indexer

Ruft die ab[`Feature`](../../feature) am angegebenen Index.

```csharp
public virtual Feature this[int index] { get; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Der Index des Features. |

### Eigentumswert

Die[`Feature`](../../feature) .

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | wird ausgelöst, wenn die Ebene schreibgeschützt geöffnet wird. |
| ArgumentOutOfRangeException | Der Index liegt außerhalb des gültigen Bereichs. |
| [GisException](../../gisexception) | Fehler beim Lesen des Features aus der Datei. |
| IOException | Ein E/A-Fehler ist aufgetreten. |

### Siehe auch

* class [Feature](../../feature)
* class [VectorLayer](../../vectorlayer)
* namensraum [Aspose.Gis](../../vectorlayer)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
