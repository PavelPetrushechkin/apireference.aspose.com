---
title: InsertAsChild
second_title: Aspose.Note for .NET API 参考
description: 获取或设置一个值该值指示是否应将插入的页面添加为上一页的子页面
type: docs
weight: 30
url: /zh/net/aspose.note/mergeoptions/insertaschild/
---
## MergeOptions.InsertAsChild property

获取或设置一个值，该值指示是否应将插入的页面添加为上一页的子页面。

```csharp
public bool InsertAsChild { get; set; }
```

### 例子

演示如何从一组 PDF 文档中导入所有页面，同时将每个 PDF 文档中的页面作为顶级 OneNote 页面的子级插入。

```csharp
string dataDir = RunExamples.GetDataDir_Import();

var d = new Document();

foreach (var file in new[] { "sampleText.pdf", "sampleImage.pdf", "sampleTable.pdf" })
{
    d.AppendChildLast(new Page()).Title = new Title() { TitleText = new RichText() { ParagraphStyle = ParagraphStyle.Default }.Append(file) };
    d.Import(Path.Combine(dataDir, file), new PdfImportOptions(), new MergeOptions() { InsertAt = int.MaxValue, InsertAsChild = true });
}

d.Save(Path.Combine(dataDir, "sample_StructuredMerge.one"));
```

### 也可以看看

* class [MergeOptions](../../mergeoptions)
* 命名空间 [Aspose.Note](../../mergeoptions)
* 部件 [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
