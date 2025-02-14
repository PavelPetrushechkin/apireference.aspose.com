---
title: LastModifiedTime
second_title: Aspose.Note for .NET API 参考
description: 获取或设置上次修改时间
type: docs
weight: 30
url: /zh/net/aspose.note/revisionsummary/lastmodifiedtime/
---
## RevisionSummary.LastModifiedTime property

获取或设置上次修改时间。

```csharp
public DateTime LastModifiedTime { get; set; }
```

### 例子

显示如何编辑页面的元信息。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_Pages();

// 加载 OneNote 文档并获取第一个孩子           
Document document = new Document(dataDir + "Aspose.one");
Page page = document.FirstChild;

// 阅读本页的内容修订摘要
var pageRevisionInfo = page.PageContentRevisionSummary;

Console.WriteLine(string.Format(
    "Author:\t{0}\nModified:\t{1}",
    pageRevisionInfo.AuthorMostRecent,
    pageRevisionInfo.LastModifiedTime.ToString("dd.MM.yyyy HH:mm:ss")));

// 更新此页面的页面修订摘要
pageRevisionInfo.AuthorMostRecent = "New Author";
pageRevisionInfo.LastModifiedTime = DateTime.Now;

document.Save(dataDir + "WorkingWithPageRevisions_out.one");
```

显示如何检查页面是否为冲突页面（即它具有 OneNote 无法自动合并的更改）。

```csharp
string dataDir = RunExamples.GetDataDir_Pages();

// 加载 OneNote 文档
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

    // 默认情况下，冲突页面只是在保存时跳过。
    // 如果将其标记为非冲突，那么它将像往常一样保存在历史记录中。
    if (historyPage.IsConflictPage)
        historyPage.IsConflictPage = false;
}

doc.Save(dataDir + "ConflictPageManipulation_out.one", SaveFormat.One);
```

### 也可以看看

* class [RevisionSummary](../../revisionsummary)
* 命名空间 [Aspose.Note](../../revisionsummary)
* 部件 [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
