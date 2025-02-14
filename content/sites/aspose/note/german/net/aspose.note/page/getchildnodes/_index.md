---
title: GetChildNodes
second_title: Aspose.Note für .NET-API-Referenz
description: Alle untergeordneten Knoten der Seite nach Knotentyp abrufen.
type: docs
weight: 150
url: /de/net/aspose.note/page/getchildnodes/
---
## Page.GetChildNodes&lt;T1&gt; method

Alle untergeordneten Knoten der Seite nach Knotentyp abrufen.

```csharp
public override List<T1> GetChildNodes<T1>()
    where T1 : class, INode
```

| Parameter | Beschreibung |
| --- | --- |
| T1 | Der Typ der Elemente in der zurückgegebenen Liste. |

### Rückgabewert

Eine Liste von untergeordneten Knoten.

### Beispiele

Zeigt, wie der gesamte Text aus dem Dokument abgerufen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Text();

// Laden Sie das Dokument in Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Text abrufen
string text = string.Join(Environment.NewLine, oneFile.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

// Text auf dem Ausgabebildschirm drucken
Console.WriteLine(text);
```

Zeigt, wie der gesamte Text von der Seite abgerufen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Text();

// Laden Sie das Dokument in Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Liste der Seitenknoten abrufen
var page = oneFile.GetChildNodes<Page>().FirstOrDefault();

if (page != null)
{
    // Text abrufen
    string text = string.Join(Environment.NewLine, page.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;
    // Text auf dem Ausgabebildschirm drucken
    Console.WriteLine(text);
}
```

Zeigt, wie man alle Seiten durchgeht und eine Ersetzung im Text vornimmt.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Text();

Dictionary<string, string> replacements = new Dictionary<string, string>();
replacements.Add("Some task here", "New Text Here");

// Laden Sie das Dokument in Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Alle RichText-Knoten abrufen
IList<RichText> textNodes = oneFile.GetChildNodes<RichText>();

foreach (RichText richText in textNodes)
{
    foreach (KeyValuePair<string, string> kvp in replacements)
    {
        // Text einer Form ersetzen
        richText.Replace(kvp.Key, kvp.Value);
    }
}

dataDir = dataDir + "ReplaceTextOnAllPages_out.pdf";

// In jedem unterstützten Dateiformat speichern
oneFile.Save(dataDir, SaveFormat.Pdf);
```

Zeigt, wie man den Text der Seite durchläuft und eine Ersetzung vornimmt.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Text();

Dictionary<string, string> replacements = new Dictionary<string, string>();
replacements.Add("voice over", "voice over new text");

// Laden Sie das Dokument in Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

IList<Page> pageNodes = oneFile.GetChildNodes<Page>();

// Alle RichText-Knoten abrufen
IList<RichText> textNodes = pageNodes[0].GetChildNodes<RichText>();

foreach (RichText richText in textNodes)
{
    foreach (KeyValuePair<string, string> kvp in replacements)
    {
        // Text einer Form ersetzen
        richText.Replace(kvp.Key, kvp.Value);
    }
}

// In jedem unterstützten Dateiformat speichern
dataDir = dataDir + "ReplaceTextOnParticularPage_out.pdf";
oneFile.Save(dataDir, SaveFormat.Pdf);
```

### Siehe auch

* interface [INode](../../inode)
* class [Page](../../page)
* namensraum [Aspose.Note](../../page)
* Montage [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
