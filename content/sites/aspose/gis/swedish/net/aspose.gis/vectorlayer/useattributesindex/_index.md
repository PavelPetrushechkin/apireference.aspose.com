---
title: UseAttributesIndex
second_title: Aspose.GIS för .NET API Referens
description: Laddar attributindex för att påskynda filtrering efter attributvärde i filtermetoder somWhereGreateraspose.gis/featuressequence/wheregreater. Om index inte finns skapas det först. Använda sig avforceRebuild för att tvinga fram indexåtergivning.
type: docs
weight: 160
url: /sv/net/aspose.gis/vectorlayer/useattributesindex/
---
## UseAttributesIndex(string, string, bool) {#useattributesindex_1}

Laddar attributindex för att påskynda filtrering efter attributvärde i filtermetoder som[`WhereGreater`](../../featuressequence/wheregreater). Om index inte finns skapas det först. Använda sig av*forceRebuild* för att tvinga fram indexåtergivning.

```csharp
public void UseAttributesIndex(string indexPath, string attributeName, bool forceRebuild = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexPath | String | Sökväg till indexfilen. |
| attributeName | String | Namn på attributet att bygga index på. |
| forceRebuild | Boolean | Om index ska återskapas även om det redan finns. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Argument är`null`. |
| ArgumentException | Attribut med ett sådant namn finns inte i lagret. |
| IOException | Ett I/O-fel uppstod. |
| InvalidOperationException | Index för det angivna attributet har redan laddats för detta lager. |
| [GisException](../../gisexception) | Filen finns och det är inte en attributindexfil skapad av Aspose.GIS. |

### Se även

* class [VectorLayer](../../vectorlayer)
* namnutrymme [Aspose.Gis](../../vectorlayer)
* hopsättning [Aspose.GIS](../../../)

---

## UseAttributesIndex(AbstractPath, string, bool) {#useattributesindex}

Laddar attributindex för att påskynda filtrering efter attributvärde i filtermetoder som[`WhereGreater`](../../featuressequence/wheregreater). Om index inte finns skapas det först. Använda sig av*forceRebuild* för att tvinga fram indexåtergivning.

```csharp
public virtual void UseAttributesIndex(AbstractPath indexPath, string attributeName, 
    bool forceRebuild = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexPath | AbstractPath | Sökväg till indexfilen. |
| attributeName | String | Namn på attributet att bygga index på. |
| forceRebuild | Boolean | Om index ska återskapas även om det redan finns. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Argument är`null`. |
| ArgumentException | Attribut med ett sådant namn finns inte i lagret. |
| IOException | Ett I/O-fel uppstod. |
| InvalidOperationException | Index för det angivna attributet har redan laddats för detta lager. |
| [GisException](../../gisexception) | Filen finns och det är inte en attributindexfil skapad av Aspose.GIS. |

### Se även

* class [AbstractPath](../../abstractpath)
* class [VectorLayer](../../vectorlayer)
* namnutrymme [Aspose.Gis](../../vectorlayer)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
