---
title: PdfImporter
second_title: Aspose.Note för .NET API-referens
description: Klassen som tillhandahåller api för att importera innehåll från dokument i PDF-format. APIet gör det möjligt att importera från PDF-dokument som finns antingen i en fil eller i en ström med angivna alternativ. Importalternativen skickas medPdfImportOptions./pdfimportoptions .
type: docs
weight: 260
url: /sv/net/aspose.note.importing/pdfimporter/
---
## PdfImporter class

Klassen som tillhandahåller api för att importera innehåll från dokument i PDF-format. API:et gör det möjligt att importera från PDF-dokument som finns antingen i en fil eller i en ström med angivna alternativ. Importalternativen skickas med[`PdfImportOptions`](../pdfimportoptions) .

```csharp
public static class PdfImporter
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Import](../../aspose.note.importing/pdfimporter/import#import)(Stream, PdfImportOptions) | Importerar innehåll i PDF-dokument från en tillhandahållen ström. |
| static [Import](../../aspose.note.importing/pdfimporter/import#import_1)(string, PdfImportOptions) | Importerar innehåll i PDF-dokument från en angiven fil. |

### Exempel

Visar hur man importerar alla sidor från PDF-dokumentgruppering var 5:e sida till en enda OneNote-sida.

```csharp
string dataDir = RunExamples.GetDataDir_Import();

var d = new Document();

var mergeOptions = new MergeOptions() { ImportAsSinglePage = true, PageSpacing = 100 };

IEnumerable<Page> pages = PdfImporter.Import(Path.Combine(dataDir, "SampleGrouping.pdf"));
while (pages.Any())
{
    d.Merge(pages.Take(5), mergeOptions);
    pages = pages.Skip(5);
}

d.Save(Path.Combine(dataDir, "sample_CustomMerge.one"));
```

### Se även

* namnutrymme [Aspose.Note.Importing](../../aspose.note.importing)
* hopsättning [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
