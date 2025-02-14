---
title: CheckBox
second_title: Aspose.Note för .NET API-referens
description: Basklassen för taggar som kan växla tillstånd mellan komplett och ofullständig.
type: docs
weight: 20
url: /sv/net/aspose.note/checkbox/
---
## CheckBox class

Basklassen för taggar som kan växla tillstånd mellan komplett och ofullständig.

```csharp
public abstract class CheckBox : ITag
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Checked](../../aspose.note/checkbox/checked) { get; } | Får ett värde som indikerar om CheckBox är i markerat tillstånd. |
| [CompletedTime](../../aspose.note/checkbox/completedtime) { get; } | Hämtar eller ställer in den slutförda tiden. |
| [CreationTime](../../aspose.note/checkbox/creationtime) { get; set; } | Hämtar eller ställer in skapelsetiden. |
| abstract [Icon](../../aspose.note/checkbox/icon) { get; } | Hämtar eller ställer in ikonen. |
| [Label](../../aspose.note/checkbox/label) { get; } | Hämtar etiketttexten. |
| [Status](../../aspose.note/checkbox/status) { get; } | Hämtar eller ställer in status. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetCompleted](../../aspose.note/checkbox/setcompleted#setcompleted)() | Ställer in taggen till slutfört läge med aktuell tid som slutförd tid. |
| [SetCompleted](../../aspose.note/checkbox/setcompleted#setcompleted_1)(DateTime) | Ställer in taggen till färdigt tillstånd. |
| virtual [SetOpen](../../aspose.note/checkbox/setopen)() | Ställer in taggen till öppet läge. |

### Exempel

Visar hur man genererar en pdf som innehåller alla sidor relaterade till 'Projekt A'.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Tags();

// Ladda dokumentet i Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, "ProjectNotes.one"));

var report = new Document();
foreach (var page in oneFile)
{
    if (page.GetChildNodes<ITaggable>().Any(e => e.Tags.Any(x => x.Label.Contains("Project A"))))
    {
        report.AppendChildLast(page.Clone());
    }
}

report.Save(Path.Combine(dataDir, "ProjectA_Report.pdf"));
```

Visar hur man gör slutförda alla kryssrutor relaterade till 'Projekt C'.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Tags();

// Ladda dokumentet i Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, "ProjectNotes.one"));

foreach (var node in oneFile.GetChildNodes<ITaggable>())
{
    foreach (var checkBox in node.Tags.OfType<CheckBox>())
    {
        if (checkBox.Label.Contains("Project C") && !checkBox.Checked)
        {
            checkBox.SetCompleted();
        }
    }
}

oneFile.Save(Path.Combine(dataDir, ClosedProjectCNotesFileName));
```

Visar hur man öppnar alla kryssrutor relaterade till 'Projekt C'.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Tags();

// Ladda dokumentet i Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, ClosedProjectCNotesFileName));

foreach (var node in oneFile.GetChildNodes<ITaggable>())
{
    foreach (var checkBox in node.Tags.OfType<CheckBox>())
    {
        if (checkBox.Label.Contains("Project C") && checkBox.Checked)
        {
            checkBox.SetOpen();
        }
    }
}

oneFile.Save(Path.Combine(dataDir, "ProjectNoteWithOpenProjectC.one"));
```

Visar hur man genererar en pdf som innehåller sidor med objekt markerade med ofullständiga kryssrutor och skapade under förra veckan.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Tags();

// Ladda dokumentet i Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, "TagFile.one"));

var report = new Document();
foreach (var page in oneFile)
{
    if (page.GetChildNodes<ITaggable>().Any(e => e.Tags.OfType<CheckBox>().Any(x => !x.Checked && DateTime.UtcNow.Subtract(TimeSpan.FromDays(7)) <= x.CreationTime)))
    {
        report.AppendChildLast(page.Clone());
    }
}

report.Save(Path.Combine(dataDir, "IncompleteLastWeekReport.pdf"));
```

Visar hur man genererar en pdf som innehåller sidor med ofullständiga uppgifter i Outlook att slutföra den här veckan.

```csharp
// Sökvägen till dokumentkatalogen.
string dataDir = RunExamples.GetDataDir_Tags();

// Ladda dokumentet i Aspose.Note.
var oneFile = new Document(Path.Combine(dataDir, "TagFile.one"));

var report = new Document();
var endOfWeek = DateTime.Today.AddDays(5 - (int)DateTime.Today.DayOfWeek);
foreach (var page in oneFile)
{
    if (page.GetChildNodes<ITaggable>().Any(e => e.Tags.OfType<NoteTask>().Any(x => !x.Checked && DateTime.UtcNow.Subtract(TimeSpan.FromDays(7)) <= x.CreationTime && x.DueDate <= endOfWeek)))
    {
        report.AppendChildLast(page.Clone());
    }
}

report.Save(Path.Combine(dataDir, "IncompleteTasksForThisWeekReport.pdf"));
```

### Se även

* interface [ITag](../itag)
* namnutrymme [Aspose.Note](../../aspose.note)
* hopsättning [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
