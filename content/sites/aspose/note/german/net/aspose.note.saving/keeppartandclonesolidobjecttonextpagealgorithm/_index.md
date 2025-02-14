---
title: KeepPartAndCloneSolidObjectToNextPageAlgorithm
second_title: Aspose.Note für .NET-API-Referenz
description: Fügt den oberen Teil des Objekts unten auf der Seite hinzu und klont das gesamte Objekt auf die nächste Seite falls es nicht auf die Originalseite passt.
type: docs
weight: 710
url: /de/net/aspose.note.saving/keeppartandclonesolidobjecttonextpagealgorithm/
---
## KeepPartAndCloneSolidObjectToNextPageAlgorithm class

Fügt den oberen Teil des Objekts unten auf der Seite hinzu und klont das gesamte Objekt auf die nächste Seite, falls es nicht auf die Originalseite passt.

```csharp
public class KeepPartAndCloneSolidObjectToNextPageAlgorithm : PageSplittingAlgorithm
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [KeepPartAndCloneSolidObjectToNextPageAlgorithm](keeppartandclonesolidobjecttonextpagealgorithm#constructor)() | Initialisiert eine neue Instanz von[`KeepPartAndCloneSolidObjectToNextPageAlgorithm`](../keeppartandclonesolidobjecttonextpagealgorithm) Klasse, unter Verwendung der Standardhöhenbegrenzung des geklonten Teils. |
| [KeepPartAndCloneSolidObjectToNextPageAlgorithm](keeppartandclonesolidobjecttonextpagealgorithm#constructor_1)(float) | Initialisiert eine neue Instanz von[`KeepPartAndCloneSolidObjectToNextPageAlgorithm`](../keeppartandclonesolidobjecttonextpagealgorithm) Klasse, mit spezifischer Höhenbegrenzung des geklonten Teils. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [HeightLimitOfClonedPart](../../aspose.note.saving/keeppartandclonesolidobjecttonextpagealgorithm/heightlimitofclonedpart) { get; } | Ruft die Höhenbegrenzung des geklonten Teils ab. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultHeightLimitOfClonedPart](../../aspose.note.saving/keeppartandclonesolidobjecttonextpagealgorithm/defaultheightlimitofclonedpart) | Die maximale Standardgröße des geklonten Teils. |

### Beispiele

Wenn lange OneNote-Seiten im PDF-Format gespeichert werden, werden sie auf Seiten aufgeteilt. Das Beispiel zeigt, wie die Aufteilungslogik von Objekten konfiguriert wird, die sich auf Seitenumbrüchen befinden.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Laden Sie das Dokument in Aspose.Note.
Document doc = new Document(dataDir + "Aspose.one");

var pdfSaveOptions = new PdfSaveOptions();

pdfSaveOptions.PageSplittingAlgorithm = new KeepPartAndCloneSolidObjectToNextPageAlgorithm(100);
// oder
pdfSaveOptions.PageSplittingAlgorithm = new KeepPartAndCloneSolidObjectToNextPageAlgorithm(400);

dataDir = dataDir + "PageSplittUsingKeepPartAndCloneSolidObjectToNextPageAlgorithm_out.pdf";
doc.Save(dataDir);
```

Wenn lange OneNote-Seiten im PDF-Format gespeichert werden, werden sie auf Seiten aufgeteilt. Das Beispiel zeigt, wie die Aufteilungslogik von Objekten konfiguriert wird, die sich auf Seitenumbrüchen befinden.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Laden Sie das Dokument in Aspose.Note.
Document doc = new Document(dataDir + "Aspose.one");
var pdfSaveOptions = new PdfSaveOptions();
pdfSaveOptions.PageSplittingAlgorithm = new AlwaysSplitObjectsAlgorithm();
// Oder
pdfSaveOptions.PageSplittingAlgorithm = new KeepPartAndCloneSolidObjectToNextPageAlgorithm();
// Oder
pdfSaveOptions.PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm();

float heightLimitOfClonedPart = 500;
pdfSaveOptions.PageSplittingAlgorithm = new KeepPartAndCloneSolidObjectToNextPageAlgorithm(heightLimitOfClonedPart);
// Oder
pdfSaveOptions.PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm(heightLimitOfClonedPart);

pdfSaveOptions.PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm(100);
// Oder
pdfSaveOptions.PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm(400);

dataDir = dataDir + "UsingKeepSOlidObjectsAlgorithm_out.pdf";
doc.Save(dataDir);
```

### Siehe auch

* class [PageSplittingAlgorithm](../pagesplittingalgorithm)
* namensraum [Aspose.Note.Saving](../../aspose.note.saving)
* Montage [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
