---
title: GetPageHistory
second_title: Aspose.Note för .NET API-referens
description: FårPageHistoryaspose.note/pagehistory som innehåller fullständig historik för varje sida som presenteras i ett dokument tidigast vid index 0. Den aktuella sidversionen kan nås somCurrentaspose.note/pagehistory/currentoch finns separat från samlingen av historiska versioner.
type: docs
weight: 100
url: /sv/net/aspose.note/document/getpagehistory/
---
## Document.GetPageHistory method

Får[`PageHistory`](../../pagehistory) som innehåller fullständig historik för varje sida som presenteras i ett dokument (tidigast vid index 0). Den aktuella sidversionen kan nås som[`Current`](../../pagehistory/current)och finns separat från samlingen av historiska versioner.

```csharp
public PageHistory GetPageHistory(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Den aktuella versionen av en sida. |

### Returvärde

Den[`PageHistory`](../../pagehistory) .

### Exempel

Visar hur man återställer tidigare version av en sida.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Pages();

// Ladda OneNote-dokument och skaffa första barn           
Document document = new Document(dataDir + "Aspose.one");
Page page = document.FirstChild;           
Page previousPageVersion = document.GetPageHistory(page).Last();

document.RemoveChild(page);
document.AppendChildLast(previousPageVersion);

document.Save(dataDir + "RollBackRevisions_out.one");
```

Visar hur man redigerar sidans historik.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Pages();

// Ladda OneNote-dokument och skaffa första barn           
Document document = new Document(dataDir + "Aspose.one");
Page page = document.FirstChild;

var pageHistory = document.GetPageHistory(page);

pageHistory.RemoveRange(0, 1);

pageHistory[0] = new Page(document);
if (pageHistory.Count > 1)
{
    pageHistory[1].Title.TitleText.Text = "New Title";

    pageHistory.Add(new Page(document));

    pageHistory.Insert(1, new Page(document));

    document.Save(dataDir + "ModifyPageHistory_out.one");
}
```

Visar hur man kontrollerar om en sida är en konfliktsida (dvs. den har ändringar som OneNote inte kunde slå samman automatiskt).

```csharp
string dataDir = RunExamples.GetDataDir_Pages();

// Ladda OneNote-dokument
Document doc = new Document(dataDir + "Aspose.one", new LoadOptions { LoadHistory = true });

var history = doc.GetPageHistory(doc.FirstChild);
for (int i = 0; i < history.Count; i++)
{
    var historyPage = history[i];
    Console.Write("    {0}. Author: {1}, {2:dd.MM.yyyy hh.mm.ss}",
                    i,
                    historyPage.PageContentRevisionSummary.AuthorMostRecent,
                    historyPage.PageContentRevisionSummary.LastModifiedTime);
    Console.WriteLine(historyPage.IsConflictPage ? ", IsConflict: true" : string.Empty);

    // Som standard hoppas konfliktsidor bara över när du sparar.
    // Om det markeras som icke-konflikt kommer det att sparas som vanligt i historiken.
    if (historyPage.IsConflictPage)
        historyPage.IsConflictPage = false;
}

doc.Save(dataDir + "ConflictPageManipulation_out.one", SaveFormat.One);
```

### Se även

* class [PageHistory](../../pagehistory)
* class [Page](../../page)
* class [Document](../../document)
* namnutrymme [Aspose.Note](../../document)
* hopsättning [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
