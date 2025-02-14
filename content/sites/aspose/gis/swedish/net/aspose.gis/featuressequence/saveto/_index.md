---
title: SaveTo
second_title: Aspose.GIS för .NET API Referens
description: Sparar funktioner sekvens till lager.
type: docs
weight: 50
url: /sv/net/aspose.gis/featuressequence/saveto/
---
## SaveTo(string, FileDriver) {#saveto_2}

Sparar funktioner sekvens till lager.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationPath | String | Sökväg till utdatalagret. |
| destinationDriver | FileDriver | Formatdrivrutinen för utdatalagret. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Alla argument är`null`. |
| [GisException](../../gisexception) | Det gick inte att läsa eller skriva funktionen till/från filen. |
| IOException | Ett I/O-fel uppstod. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation av funktioners geometri från källans rumsliga referenssystem till det rumsliga referenssystemet för målet misslyckades. |

### Se även

* class [FileDriver](../../filedriver)
* class [FeaturesSequence](../../featuressequence)
* namnutrymme [Aspose.Gis](../../featuressequence)
* hopsättning [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver) {#saveto}

Sparar funktioner sekvens till lager.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationPath | AbstractPath | Sökväg till utdatalagret. |
| destinationDriver | FileDriver | Formatdrivrutinen för utdatalagret. |

### Undantag

| undantag | skick |
| --- | --- |
| [GisException](../../gisexception) | Det gick inte att läsa eller skriva funktionen till/från filen. |
| IOException | Ett I/O-fel uppstod. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation av funktioners geometri från källans rumsliga referenssystem till det rumsliga referenssystemet för målet misslyckades. |

### Se även

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [FeaturesSequence](../../featuressequence)
* namnutrymme [Aspose.Gis](../../featuressequence)
* hopsättning [Aspose.GIS](../../../)

---

## SaveTo(string, FileDriver, SavingOptions) {#saveto_3}

Sparar funktioner sekvens till lager.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver, SavingOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationPath | String | Sökväg till utdatalagret. |
| destinationDriver | FileDriver | Formatdrivrutinen för utdatalagret. |
| options | SavingOptions | Alternativ för sparproceduren. |

### Undantag

| undantag | skick |
| --- | --- |
| [GisException](../../gisexception) | Det gick inte att läsa eller skriva funktionen till/från filen. |
| IOException | Ett I/O-fel uppstod. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation av funktioners geometri från källans rumsliga referenssystem till det rumsliga referenssystemet för målet misslyckades. |
| NotSupportedException | Rumsligt referenssystem specificerat i*options*stöds inte av*destinationDriver* . |

### Se även

* class [FileDriver](../../filedriver)
* class [SavingOptions](../../savingoptions)
* class [FeaturesSequence](../../featuressequence)
* namnutrymme [Aspose.Gis](../../featuressequence)
* hopsättning [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver, SavingOptions) {#saveto_1}

Sparar funktioner sekvens till lager.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver, 
    SavingOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destinationPath | AbstractPath | Sökväg till utdatalagret. |
| destinationDriver | FileDriver | Formatdrivrutinen för utdatalagret. |
| options | SavingOptions | Alternativ för sparproceduren. |

### Undantag

| undantag | skick |
| --- | --- |
| [GisException](../../gisexception) | Det gick inte att läsa eller skriva funktionen till/från filen. |
| IOException | Ett I/O-fel uppstod. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation av funktioners geometri från källans rumsliga referenssystem till det rumsliga referenssystemet för målet misslyckades. |
| NotSupportedException | Rumsligt referenssystem specificerat i*options*stöds inte av*destinationDriver* . |

### Se även

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [SavingOptions](../../savingoptions)
* class [FeaturesSequence](../../featuressequence)
* namnutrymme [Aspose.Gis](../../featuressequence)
* hopsättning [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
