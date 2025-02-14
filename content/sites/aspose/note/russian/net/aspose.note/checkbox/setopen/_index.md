---
title: SetOpen
second_title: Справочник по API Aspose.Note для .NET
description: Устанавливает тег в открытое состояние.
type: docs
weight: 80
url: /ru/net/aspose.note/checkbox/setopen/
---
## CheckBox.SetOpen method

Устанавливает тег в открытое состояние.

```csharp
public virtual void SetOpen()
```

### Примеры

Показывает, как открыть все элементы флажка, связанные с «Проектом C».

```csharp
// Путь к каталогу документов.
string dataDir = RunExamples.GetDataDir_Tags();

// Загрузите документ в Aspose.Note.
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

### Смотрите также

* class [CheckBox](../../checkbox)
* пространство имен [Aspose.Note](../../checkbox)
* сборка [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
