---
title: LoadOptions
second_title: Aspose.Note for .NET API Referansı
description: Belge yüklemek için kullanılan seçenekler.
type: docs
weight: 300
url: /tr/net/aspose.note/loadoptions/
---
## LoadOptions class

Belge yüklemek için kullanılan seçenekler.

```csharp
public class LoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LoadOptions](loadoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DocumentPassword](../../aspose.note/loadoptions/documentpassword) { get; set; } | Şifrelenmiş belge içeriği için bir parola alır veya ayarlar. Belgenin parola korumalı olmaması durumunda değer yok sayılır. |
| [LoadHistory](../../aspose.note/loadoptions/loadhistory) { get; set; } | Belge yükleyicinin geçmişi yok sayması gerekip gerekmediğini belirten bir değer alır veya ayarlar. Bellek ve CPU kullanımını azaltmak için bu seçeneği kullanın. Varsayılan değer:`doğru` . |

### Örnekler

Şifrelenmiş bir belgenin nasıl yapıldığını gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

LoadOptions loadOptions = new LoadOptions { DocumentPassword = "password" };
Document doc = new Document(dataDir + "Sample1.one", loadOptions);
```

Şifreli bir not defterinin nasıl yapıldığını gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_NoteBook();
var notebook = new Notebook(dataDir + "test.onetoc2", new NotebookLoadOptions() { DeferredLoading = true });

notebook.LoadChildDocument(dataDir + "Aspose.one");  
notebook.LoadChildDocument(dataDir + "Locked Pass1.one", new LoadOptions() { DocumentPassword = "pass" });
notebook.LoadChildDocument(dataDir + "Locked Pass2.one", new LoadOptions() { DocumentPassword = "pass2" });
```

Sayfanın geçmişinin nasıl alınacağını gösterir.

```csharp
// Belgeler dizininin yolu.
string dataDir = RunExamples.GetDataDir_Pages();

// OneNote belgesini yükle
Document document = new Document(dataDir + "Aspose.one", new LoadOptions { LoadHistory = true });

// İlk sayfayı al
Page firstPage = document.FirstChild;
foreach (Page pageRevision in document.GetPageHistory(firstPage))
{
    /*Use pageRevision like a regular page.*/
    Console.WriteLine("LastModifiedTime: {0}", pageRevision.LastModifiedTime);
    Console.WriteLine("CreationTime: {0}", pageRevision.CreationTime);
    Console.WriteLine("Title: {0}", pageRevision.Title);
    Console.WriteLine("Level: {0}", pageRevision.Level);
    Console.WriteLine("Author: {0}", pageRevision.Author);
    Console.WriteLine();
}
```

### Ayrıca bakınız

* ad alanı [Aspose.Note](../../aspose.note)
* toplantı [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
