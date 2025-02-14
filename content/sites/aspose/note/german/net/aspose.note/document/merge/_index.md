---
title: Merge
second_title: Aspose.Note für .NET-API-Referenz
description: Führt eine Reihe von Seiten mit dem Dokument zusammen.
type: docs
weight: 120
url: /de/net/aspose.note/document/merge/
---
## Document.Merge method

Führt eine Reihe von Seiten mit dem Dokument zusammen.

```csharp
public Document Merge(IEnumerable<Page> pages, MergeOptions mergeOptions = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pages | IEnumerable`1 | Eine Reihe von Seiten. |
| mergeOptions | MergeOptions | Gibt die Optionen an, wie bereitgestellte Seiten zusammengeführt werden. |

### Rückgabewert

Gibt die Referenz auf das Dokument zurück.

### Beispiele

Zeigt, wie alle Seiten aus einem PDF-Dokument importiert werden, das alle 5 Seiten auf eine einzelne OneNote-Seite gruppiert.

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

### Siehe auch

* class [Page](../../page)
* class [MergeOptions](../../mergeoptions)
* class [Document](../../document)
* namensraum [Aspose.Note](../../document)
* Montage [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
