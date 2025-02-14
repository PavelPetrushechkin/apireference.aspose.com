---
title: Table
second_title: Aspose.Note für .NET-API-Referenz
description: Stellt eine Tabelle dar.
type: docs
weight: 870
url: /de/net/aspose.note/table/
---
## Table class

Stellt eine Tabelle dar.

```csharp
public sealed class Table : CompositeNode<TableRow>, IOutlineElementChildNode, ITaggable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Table](table#constructor)() | Initialisiert eine neue Instanz von[`Table`](../table) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Columns](../../aspose.note/table/columns) { get; } | Ruft die Spalten der Tabelle ab. |
| [Document](../../aspose.note/node/document) { get; } | Ruft das Dokument des Knotens ab. |
| [FirstChild](../../aspose.note/compositenode`1/firstchild) { get; } |  |
| [IsBordersVisible](../../aspose.note/table/isbordersvisible) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Tabellenrahmen sichtbar ist. |
| [IsComposite](../../aspose.note/compositenode`1/iscomposite) { get; } |  |
| [LastChild](../../aspose.note/compositenode`1/lastchild) { get; } |  |
| [LastModifiedTime](../../aspose.note/table/lastmodifiedtime) { get; set; } | Ruft die letzte Änderungszeit ab oder setzt sie. |
| [NextSibling](../../aspose.note/node/nextsibling) { get; } | Ruft den nächsten Knoten auf derselben Knotenbaumebene ab. |
| [NodeType](../../aspose.note/node/nodetype) { get; } | Ruft den Knotentyp ab. |
| [ParentNode](../../aspose.note/node/parentnode) { get; } | Ruft den übergeordneten Knoten ab. |
| [PreviousSibling](../../aspose.note/node/previoussibling) { get; } | Ruft den vorherigen Knoten auf derselben Knotenbaumebene ab. |
| [Tags](../../aspose.note/table/tags) { get; } | Ruft die Liste aller Tags eines Absatzes ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.note/table/accept)(DocumentVisitor) | Akzeptiert den Besucher des Knotens. |
| virtual [AppendChildFirst&lt;T1&gt;](../../aspose.note/compositenode`1/appendchildfirst)(T1) |  |
| virtual [AppendChildLast&lt;T1&gt;](../../aspose.note/compositenode`1/appendchildlast)(T1) |  |
| override [GetChildNodes&lt;T1&gt;](../../aspose.note/compositenode`1/getchildnodes)() |  |
| [GetEnumerator](../../aspose.note/compositenode`1/getenumerator)() |  |
| virtual [InsertChild&lt;T1&gt;](../../aspose.note/compositenode`1/insertchild)(int, T1) |  |
| [InsertChildrenRange](../../aspose.note/compositenode`1/insertchildrenrange)(int, IEnumerable&lt;TableRow&gt;) |  |
| [InsertChildrenRange](../../aspose.note/compositenode`1/insertchildrenrange)(int, params TableRow[]) |  |
| [RemoveChild&lt;T1&gt;](../../aspose.note/compositenode`1/removechild)(T1) |  |

### Beispiele

Zeigt, wie Text aus jeder Tabellenzeile abgerufen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tables();

// Laden Sie das Dokument in Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Holen Sie sich eine Liste von Tabellenknoten
IList<Table> nodes = document.GetChildNodes<Table>();

foreach (Table table in nodes)
{
    // Tabellenzeilen durchlaufen
    foreach (TableRow row in table)
    {
        // Text abrufen
        string text = string.Join(Environment.NewLine, row.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

        // Text auf dem Ausgabebildschirm drucken
        Console.WriteLine(text);
    }
}
```

Zeigt, wie Text aus einer Tabelle abgerufen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tables();

// Laden Sie das Dokument in Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Holen Sie sich eine Liste von Tabellenknoten
IList<Table> nodes = document.GetChildNodes<Table>();

// Tabellenanzahl setzen
int tblCount = 0;

foreach (Table table in nodes)
{
    tblCount++;
    Console.WriteLine("table # " + tblCount);

    // Text abrufen
    string text = string.Join(Environment.NewLine, table.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

    // Text auf dem Ausgabebildschirm drucken
    Console.WriteLine(text);
}
```

Zeigt, wie Text aus den Zellen einer Tabelle abgerufen wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tables();

// Laden Sie das Dokument in Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Holen Sie sich eine Liste von Tabellenknoten
IList<Table> nodes = document.GetChildNodes<Table>();        

foreach (Table table in nodes)
{
    // Tabellenzeilen durchlaufen
    foreach (TableRow row in table)
    {
        // Liste der TableCell-Knoten abrufen
        // Durch Tabellenzellen iterieren
        foreach (TableCell cell in row)
        {
            // Text abrufen
            string text = string.Join(Environment.NewLine, cell.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

            // Text auf dem Ausgabebildschirm drucken
            Console.WriteLine(text);
        }
    }
}
```

Zeigt, wie eine Hintergrundfarbe für eine Zelle festgelegt wird.

```csharp
// Erstellen Sie ein Objekt der Document-Klasse
Document doc = new Document();

// Objekt der TableCell-Klasse initialisieren und Textinhalt festlegen
TableCell cell11 = new TableCell(doc);
cell11.AppendChildLast(InsertTable.GetOutlineElementWithText(doc, "Small text"));
cell11.BackgroundColor = Color.Coral;

// TableRow-Klassenobjekt initialisieren
TableRow row = new TableRow(doc);
row.AppendChildLast(cell11);

Table table = new Table(doc)
              {
                  IsBordersVisible = true,
                  Columns = { new TableColumn() { Width = 200 } }
              };
table.AppendChildLast(row);

OutlineElement oe = new OutlineElement(doc);
oe.AppendChildLast(table);

Outline o = new Outline(doc);
o.AppendChildLast(oe);

// Seitenklassenobjekt initialisieren
Page page = new Page(doc);
page.AppendChildLast(o);

doc.AppendChildLast(page);

doc.Save(Path.Combine(RunExamples.GetDataDir_Tables(), "SettingCellBackGroundColor.pdf"));
```

Zeigt, wie man eine neue Tabelle mit Tag hinzufügt.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tags();

// Erstellen Sie ein Objekt der Document-Klasse
Document doc = new Document();

// Seitenklassenobjekt initialisieren
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// TableRow-Klassenobjekt initialisieren
TableRow row = new TableRow(doc);

// TableCell-Klassenobjekt initialisieren
TableCell cell = new TableCell(doc);

// Zellinhalt einfügen
cell.AppendChildLast(InsertTable.GetOutlineElementWithText(doc, "Single cell."));

// Zelle zum Zeilenknoten hinzufügen
row.AppendChildLast(cell);

// Tabellenknoten initialisieren
Table table = new Table(doc)
              {
                  IsBordersVisible = true,
                  Columns = { new TableColumn { Width = 70 } }
              };

// Zeilenknoten in Tabelle einfügen
table.AppendChildLast(row);

// Tag zu diesem Tabellenknoten hinzufügen
table.Tags.Add(NoteTag.CreateQuestionMark());

Outline outline = new Outline(doc);
OutlineElement outlineElem = new OutlineElement(doc);

// Tabellenknoten hinzufügen
outlineElem.AppendChildLast(table);

// Gliederungselemente hinzufügen
outline.AppendChildLast(outlineElem);
page.AppendChildLast(outline);
doc.AppendChildLast(page);

// OneNote-Dokument speichern
dataDir = dataDir + "AddTableNodeWithTag_out.one";
doc.Save(dataDir);
```

Zeigt, wie eine Tabelle mit einer gesperrten Spalte erstellt wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tables();

// Erstellen Sie ein Objekt der Document-Klasse
Document doc = new Document();

// Seitenklassenobjekt initialisieren
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// TableRow-Klassenobjekt initialisieren
TableRow row1 = new TableRow(doc);

// Objekt der TableCell-Klasse initialisieren und Textinhalt festlegen
TableCell cell11 = new TableCell(doc);
cell11.AppendChildLast(InsertTable.GetOutlineElementWithText(doc, "Small text"));
row1.AppendChildLast(cell11);

// TableRow-Klassenobjekt initialisieren
TableRow row2 = new TableRow(doc);

// Objekt der TableCell-Klasse initialisieren und Textinhalt festlegen
TableCell cell21 = new TableCell(doc);
cell21.AppendChildLast(InsertTable.GetOutlineElementWithText(doc, "Long   text    with    several   words and    spaces."));
row2.AppendChildLast(cell21);

// Tabellenklassenobjekt initialisieren
Table table = new Table(doc)
              {
                  IsBordersVisible = true,
                  Columns = { new TableColumn { Width = 70, LockedWidth = true } }
              };

// Zeilen hinzufügen
table.AppendChildLast(row1);
table.AppendChildLast(row2);

Outline outline = new Outline(doc);
OutlineElement outlineElem = new OutlineElement(doc);

// Tabellenknoten hinzufügen
outlineElem.AppendChildLast(table);

// Gliederungselementknoten hinzufügen
outline.AppendChildLast(outlineElem);

// Gliederungsknoten hinzufügen
page.AppendChildLast(outline);

// Seitenknoten hinzufügen
doc.AppendChildLast(page);
dataDir = dataDir + "CreateTableWithLockedColumns_out.one";
doc.Save(dataDir);
```

Zeigt, wie eine neue Tabelle erstellt wird.

```csharp
// Der Pfad zum Dokumentenverzeichnis.
string dataDir = RunExamples.GetDataDir_Tables();

// Erstellen Sie ein Objekt der Document-Klasse
Document doc = new Document();

// Seitenklassenobjekt initialisieren
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// TableRow-Klassenobjekt initialisieren
TableRow row1 = new TableRow(doc);

// Objekte der TableCell-Klasse initialisieren
TableCell cell11 = new TableCell(doc);
TableCell cell12 = new TableCell(doc);
TableCell cell13 = new TableCell(doc);

// Gliederungselemente in die Tabellenzelle einfügen
cell11.AppendChildLast(GetOutlineElementWithText(doc, "cell_1.1"));
cell12.AppendChildLast(GetOutlineElementWithText(doc, "cell_1.2"));
cell13.AppendChildLast(GetOutlineElementWithText(doc, "cell_1.3"));

// Tabellenzellen zu Zeilen
row1.AppendChildLast(cell11);
row1.AppendChildLast(cell12);
row1.AppendChildLast(cell13);

// TableRow-Klassenobjekt initialisieren
TableRow row2 = new TableRow(doc);

// Objekte der TableCell-Klasse initialisieren
TableCell cell21 = new TableCell(doc);
TableCell cell22 = new TableCell(doc);
TableCell cell23 = new TableCell(doc);

// Gliederungselemente in die Tabellenzelle einfügen
cell21.AppendChildLast(GetOutlineElementWithText(doc, "cell_2.1"));
cell22.AppendChildLast(GetOutlineElementWithText(doc, "cell_2.2"));
cell23.AppendChildLast(GetOutlineElementWithText(doc, "cell_2.3"));

// Tabellenzellen an Zeilen anhängen
row2.AppendChildLast(cell21);
row2.AppendChildLast(cell22);
row2.AppendChildLast(cell23);

// Tabellenklassenobjekt initialisieren und Spaltenbreiten festlegen
Table table = new Table(doc)
              {
                  IsBordersVisible = true,
                  Columns = { new TableColumn { Width = 200 }, new TableColumn { Width = 200 }, new TableColumn { Width = 200 } }
              };

// Tabellenzeilen an Tabelle anhängen
table.AppendChildLast(row1);
table.AppendChildLast(row2);

// Outline-Objekt initialisieren
Outline outline = new Outline(doc);

// OutlineElement-Objekt initialisieren
OutlineElement outlineElem = new OutlineElement(doc);

// Tabelle zum Gliederungselementknoten hinzufügen
outlineElem.AppendChildLast(table);

// Gliederungselement zur Gliederung hinzufügen
outline.AppendChildLast(outlineElem);

// Gliederung zum Seitenknoten hinzufügen
page.AppendChildLast(outline);

// Seite zum Dokumentknoten hinzufügen
doc.AppendChildLast(page);
dataDir = dataDir + "InsertTable_out.one";
doc.Save(dataDir);
```

### Siehe auch

* class [CompositeNode&lt;T&gt;](../compositenode-1)
* class [TableRow](../tablerow)
* interface [IOutlineElementChildNode](../ioutlineelementchildnode)
* interface [ITaggable](../itaggable)
* namensraum [Aspose.Note](../../aspose.note)
* Montage [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
