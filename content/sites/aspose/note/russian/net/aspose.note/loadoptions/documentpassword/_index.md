---
title: DocumentPassword
second_title: Справочник по API Aspose.Note для .NET
description: Получает или задает пароль для зашифрованного содержимого документа. Значение игнорируется если документ не защищен паролем.
type: docs
weight: 20
url: /ru/net/aspose.note/loadoptions/documentpassword/
---
## LoadOptions.DocumentPassword property

Получает или задает пароль для зашифрованного содержимого документа. Значение игнорируется, если документ не защищен паролем.

```csharp
public string DocumentPassword { get; set; }
```

### Примеры

Показывает, как зашифровать документ.

```csharp
// Путь к каталогу документов.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

LoadOptions loadOptions = new LoadOptions { DocumentPassword = "password" };
Document doc = new Document(dataDir + "Sample1.one", loadOptions);
```

Показывает, как зашифровать блокнот.

```csharp
// Путь к каталогу документов.
string dataDir = RunExamples.GetDataDir_NoteBook();
var notebook = new Notebook(dataDir + "test.onetoc2", new NotebookLoadOptions() { DeferredLoading = true });

notebook.LoadChildDocument(dataDir + "Aspose.one");  
notebook.LoadChildDocument(dataDir + "Locked Pass1.one", new LoadOptions() { DocumentPassword = "pass" });
notebook.LoadChildDocument(dataDir + "Locked Pass2.one", new LoadOptions() { DocumentPassword = "pass2" });
```

### Смотрите также

* class [LoadOptions](../../loadoptions)
* пространство имен [Aspose.Note](../../loadoptions)
* сборка [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
