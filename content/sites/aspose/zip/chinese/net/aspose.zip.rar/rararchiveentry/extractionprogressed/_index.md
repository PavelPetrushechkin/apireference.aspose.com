---
title: ExtractionProgressed
second_title: Aspose.ZIP for .NET API 参考
description: 提取原始流的一部分时引发
type: docs
weight: 80
url: /zh/net/aspose.zip.rar/rararchiveentry/extractionprogressed/
---
## RarArchiveEntry.ExtractionProgressed event

提取原始流的一部分时引发。

```csharp
public event EventHandler<ProgressEventArgs> ExtractionProgressed;
```

### 评论

事件发送者是[`RarArchiveEntry`](../../rararchiveentry)实例。

### 例子

```csharp
archive.Entries[0].ExtractionProgressed += (s, e) => {  int percent = (int)((100 * e.ProceededBytes) / ((RarArchiveEntry)s).UncompressedSize); };
```

### 也可以看看

* class [ProgressEventArgs](../../../aspose.zip/progresseventargs)
* class [RarArchiveEntry](../../rararchiveentry)
* 命名空间 [Aspose.Zip.Rar](../../rararchiveentry)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
