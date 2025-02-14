---
title: FirstChild
second_title: Aspose.Note for .NET API Referansı
description: Bu düğümün ilk alt düğümünü alır.
type: docs
weight: 10
url: /tr/net/aspose.note/compositenode-1/firstchild/
---
## CompositeNode&lt;T&gt;.FirstChild property

Bu düğümün ilk alt düğümünü alır.

```csharp
public T FirstChild { get; }
```

### Örnekler

Bir sayfanın çakışma sayfası olup olmadığının nasıl kontrol edileceğini gösterir (yani, OneNote'un otomatik olarak birleştiremeyeceği değişikliklere sahiptir).

```csharp
string dataDir = RunExamples.GetDataDir_Pages();

// OneNote belgesini yükle
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

    // Varsayılan olarak çakışan sayfalar kaydedilirken atlanır.
    // Çakışmaz olarak işaretlerseniz, tarihte her zamanki gibi kaydedilecektir.
    if (historyPage.IsConflictPage)
        historyPage.IsConflictPage = false;
}

doc.Save(dataDir + "ConflictPageManipulation_out.one", SaveFormat.One);
```

### Ayrıca bakınız

* class [CompositeNode&lt;T&gt;](../../compositenode-1)
* ad alanı [Aspose.Note](../../compositenode-1)
* toplantı [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
