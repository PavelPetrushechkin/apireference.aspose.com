---
title: Extract
second_title: Aspose.ZIP for .NET API 参考
description: 将存档提取到提供的流中
type: docs
weight: 30
url: /zh/net/aspose.zip.bzip2/bzip2archive/extract/
---
## Bzip2Archive.Extract method

将存档提取到提供的流中。

```csharp
public void Extract(Stream destination)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destination | Stream | 目标流。必须是可写的。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | *destination*不支持书写。 |

### 例子

```csharp
using (Bzip2Archive archive = new Bzip2Archive("archive.bz2"))
{
     archive.Extract(httpResponseStream);
}
```

### 也可以看看

* class [Bzip2Archive](../../bzip2archive)
* 命名空间 [Aspose.Zip.Bzip2](../../bzip2archive)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
