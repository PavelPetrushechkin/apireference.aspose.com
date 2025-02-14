---
title: OriginalWidth
second_title: Aspose.Note for .NET API 参考
description: 获取原始宽度这是调整大小之前图像的原始宽度
type: docs
weight: 150
url: /zh/net/aspose.note/image/originalwidth/
---
## Image.OriginalWidth property

获取原始宽度。这是调整大小之前图像的原始宽度。

```csharp
public float OriginalWidth { get; }
```

### 例子

显示如何获取图像的元信息。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_Images();

// 将文档加载到 Aspose.Note。
Document oneFile = new Document(dataDir + "Aspose.one");

// 获取所有图像节点
IList<Aspose.Note.Image> images = oneFile.GetChildNodes<Aspose.Note.Image>();

foreach (Aspose.Note.Image image in images)
{
    Console.WriteLine("Width: {0}", image.Width);
    Console.WriteLine("Height: {0}", image.Height);
    Console.WriteLine("OriginalWidth: {0}", image.OriginalWidth);
    Console.WriteLine("OriginalHeight: {0}", image.OriginalHeight);
    Console.WriteLine("FileName: {0}", image.FileName);
    Console.WriteLine("LastModifiedTime: {0}", image.LastModifiedTime);
    Console.WriteLine();
}
```

### 也可以看看

* class [Image](../../image)
* 命名空间 [Aspose.Note](../../image)
* 部件 [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
