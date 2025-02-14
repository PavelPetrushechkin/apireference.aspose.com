---
title: Language
second_title: Справочник по API Aspose.Note для .NET
description: Получает или задает язык текста.
type: docs
weight: 100
url: /ru/net/aspose.note/textstyle/language/
---
## TextStyle.Language property

Получает или задает язык текста.

```csharp
public CultureInfo Language { get; set; }
```

### Примечания

ВозвращаетInvariantCulture если свойство не установлено.

### Примеры

Установите язык проверки для текста.

```csharp
var document = new Document();
var page = new Page();
var outline = new Outline();
var outlineElem = new OutlineElement();

var text = new RichText() { ParagraphStyle = ParagraphStyle.Default };
text.Append("United States", new TextStyle() { Language = CultureInfo.GetCultureInfo("en-US") })
    .Append(" Germany", new TextStyle() { Language = CultureInfo.GetCultureInfo("de-DE") })
    .Append(" China", new TextStyle() { Language = CultureInfo.GetCultureInfo("zh-CN") });

outlineElem.AppendChildLast(text);
outline.AppendChildLast(outlineElem);
page.AppendChildLast(outline);
document.AppendChildLast(page);

document.Save(Path.Combine(RunExamples.GetDataDir_Text(), "SetProofingLanguageForText.one"));
```

### Смотрите также

* class [TextStyle](../../textstyle)
* пространство имен [Aspose.Note](../../textstyle)
* сборка [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
