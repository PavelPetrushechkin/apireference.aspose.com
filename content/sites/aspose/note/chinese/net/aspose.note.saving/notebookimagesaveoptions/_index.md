---
title: NotebookImageSaveOptions
second_title: Aspose.Note for .NET API 参考
description: 允许在将笔记本页面渲染为图像时指定其他选项
type: docs
weight: 740
url: /zh/net/aspose.note.saving/notebookimagesaveoptions/
---
## NotebookImageSaveOptions class

允许在将笔记本页面渲染为图像时指定其他选项。

```csharp
public class NotebookImageSaveOptions : NotebookSaveOptions<ImageSaveOptions>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [NotebookImageSaveOptions](notebookimagesaveoptions)(SaveFormat) | 初始化[`NotebookImageSaveOptions`](../notebookimagesaveoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DeferredSaving](../../aspose.note.saving/notebooksaveoptions/deferredsaving) { get; set; } | 获取或设置一个值，该值指示是否应显式保存子文档 。 |
| [DocumentSaveOptions](../../aspose.note.saving/notebooksaveoptions`1/documentsaveoptions) { get; } |  |
| [Flatten](../../aspose.note.saving/notebooksaveoptions/flatten) { get; set; } | 获取或设置一个值，该值指示笔记本子层次结构是否平展保存。 |
| override [SaveFormat](../../aspose.note.saving/notebooksaveoptions`1/saveformat) { get; } |  |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetDocumentSaveOptions](../../aspose.note.saving/notebooksaveoptions`1/getdocumentsaveoptions)() |  |

### 例子

展示如何以 pdf 格式保存扁平化的笔记本。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_NoteBook();

// 加载 OneNote 笔记本
var notebook = new Notebook(dataDir + "Notizbuch �ffnen.onetoc2");

// 保存笔记本
dataDir = dataDir + "ConvertToPDFAsFlattened_out.pdf";
notebook.Save(
    dataDir,
    new NotebookPdfSaveOptions
    {
        Flatten = true
    });
```

显示如何使用指定选项将笔记本保存为图像。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_NoteBook();

// 加载 OneNote 笔记本
var notebook = new Notebook(dataDir + "Notizbuch �ffnen.onetoc2");

var notebookSaveOptions = new NotebookImageSaveOptions(SaveFormat.Png);

var documentSaveOptions = notebookSaveOptions.DocumentSaveOptions;

documentSaveOptions.Resolution = 400;

dataDir = dataDir + "ConvertToImageWithOptions_out.png";

// 保存笔记本
notebook.Save(dataDir, notebookSaveOptions);
```

显示如何将展平的笔记本另存为图像。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_NoteBook();

// 加载 OneNote 笔记本
var notebook = new Notebook(dataDir + "Notizbuch öffnen.onetoc2");

var notebookSaveOptions = new NotebookImageSaveOptions(SaveFormat.Png);

var documentSaveOptions = notebookSaveOptions.DocumentSaveOptions;

documentSaveOptions.Resolution = 400;
notebookSaveOptions.Flatten = true;

dataDir = dataDir + "ConvertToImageAsFlattenedNotebook_out.png";

// 保存笔记本
notebook.Save(dataDir, notebookSaveOptions);
```

### 也可以看看

* class [NotebookSaveOptions&lt;TDocumentSaveOptions&gt;](../notebooksaveoptions-1)
* class [ImageSaveOptions](../imagesaveoptions)
* 命名空间 [Aspose.Note.Saving](../../aspose.note.saving)
* 部件 [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
