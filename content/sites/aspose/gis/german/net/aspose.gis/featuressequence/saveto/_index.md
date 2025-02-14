---
title: SaveTo
second_title: Aspose.GIS für .NET-API-Referenz
description: Speichert die FeatureSequenz im Layer.
type: docs
weight: 50
url: /de/net/aspose.gis/featuressequence/saveto/
---
## SaveTo(string, FileDriver) {#saveto_2}

Speichert die Feature-Sequenz im Layer.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationPath | String | Pfad zur Ausgabeschicht. |
| destinationDriver | FileDriver | Der Formattreiber für die Ausgabeschicht. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Jedes Argument ist`null`. |
| [GisException](../../gisexception) | Fehler beim Lesen oder Schreiben des Features in/aus der Datei. |
| IOException | Ein E/A-Fehler ist aufgetreten. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation der Feature-Geometrie vom Raumbezugssystem der Quelle zum Raumbezugssystem des Ziels fehlgeschlagen. |

### Siehe auch

* class [FileDriver](../../filedriver)
* class [FeaturesSequence](../../featuressequence)
* namensraum [Aspose.Gis](../../featuressequence)
* Montage [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver) {#saveto}

Speichert die Feature-Sequenz im Layer.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationPath | AbstractPath | Pfad zur Ausgabeschicht. |
| destinationDriver | FileDriver | Der Formattreiber für die Ausgabeschicht. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [GisException](../../gisexception) | Fehler beim Lesen oder Schreiben des Features in/aus der Datei. |
| IOException | Ein E/A-Fehler ist aufgetreten. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation der Feature-Geometrie vom Raumbezugssystem der Quelle zum Raumbezugssystem des Ziels fehlgeschlagen. |

### Siehe auch

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [FeaturesSequence](../../featuressequence)
* namensraum [Aspose.Gis](../../featuressequence)
* Montage [Aspose.GIS](../../../)

---

## SaveTo(string, FileDriver, SavingOptions) {#saveto_3}

Speichert die Feature-Sequenz im Layer.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver, SavingOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationPath | String | Pfad zur Ausgabeschicht. |
| destinationDriver | FileDriver | Der Formattreiber für die Ausgabeschicht. |
| options | SavingOptions | Optionen für den Speichervorgang. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [GisException](../../gisexception) | Fehler beim Lesen oder Schreiben des Features in/aus der Datei. |
| IOException | Ein E/A-Fehler ist aufgetreten. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation der Feature-Geometrie vom Raumbezugssystem der Quelle zum Raumbezugssystem des Ziels fehlgeschlagen. |
| NotSupportedException | Räumliches Bezugssystem angegeben in*options*wird nicht unterstützt von*destinationDriver* . |

### Siehe auch

* class [FileDriver](../../filedriver)
* class [SavingOptions](../../savingoptions)
* class [FeaturesSequence](../../featuressequence)
* namensraum [Aspose.Gis](../../featuressequence)
* Montage [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver, SavingOptions) {#saveto_1}

Speichert die Feature-Sequenz im Layer.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver, 
    SavingOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationPath | AbstractPath | Pfad zur Ausgabeschicht. |
| destinationDriver | FileDriver | Der Formattreiber für die Ausgabeschicht. |
| options | SavingOptions | Optionen für den Speichervorgang. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [GisException](../../gisexception) | Fehler beim Lesen oder Schreiben des Features in/aus der Datei. |
| IOException | Ein E/A-Fehler ist aufgetreten. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | Transformation der Feature-Geometrie vom Raumbezugssystem der Quelle zum Raumbezugssystem des Ziels fehlgeschlagen. |
| NotSupportedException | Räumliches Bezugssystem angegeben in*options*wird nicht unterstützt von*destinationDriver* . |

### Siehe auch

* class [AbstractPath](../../abstractpath)
* class [FileDriver](../../filedriver)
* class [SavingOptions](../../savingoptions)
* class [FeaturesSequence](../../featuressequence)
* namensraum [Aspose.Gis](../../featuressequence)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
