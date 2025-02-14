---
title: SnappyArchive
second_title: Aspose.ZIP for .NET API 参考
description: 初始化SnappyArchiveaspose.zip.snappy/snappyarchive准备压缩的类
type: docs
weight: 10
url: /zh/net/aspose.zip.snappy/snappyarchive/snappyarchive/
---
## SnappyArchive() {#constructor}

初始化[`SnappyArchive`](../../snappyarchive)准备压缩的类。

```csharp
public SnappyArchive()
```

### 例子

以下示例显示如何压缩文件。

```csharp
using (SnappyArchive archive = new SnappyArchive()) 
{
    archive.SetSource("data.bin");
    archive.Save("archive.snapy");
}
```

### 也可以看看

* class [SnappyArchive](../../snappyarchive)
* 命名空间 [Aspose.Zip.Snappy](../../snappyarchive)
* 部件 [Aspose.Zip](../../../)

---

## SnappyArchive(Stream) {#constructor_1}

初始化[`SnappyArchive`](../../snappyarchive)准备解压的类。

```csharp
public SnappyArchive(Stream source)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 存档的来源。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | *source*是不可搜索的。 |
| ArgumentNullException | *source*一片空白。 |

### 评论

此构造函数不解压缩。看[`Extract`](../extract)解压方法.

### 也可以看看

* class [SnappyArchive](../../snappyarchive)
* 命名空间 [Aspose.Zip.Snappy](../../snappyarchive)
* 部件 [Aspose.Zip](../../../)

---

## SnappyArchive(string) {#constructor_2}

初始化[`SnappyArchive`](../../snappyarchive)准备解压的类。

```csharp
public SnappyArchive(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 存档源的路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *path*一片空白。 |
| SecurityException | 调用者没有所需的访问权限 |
| ArgumentException | 这*path*为空、仅包含空格或包含无效字符。 |
| UnauthorizedAccessException | 访问文件*path*被拒绝。 |
| PathTooLongException | 指定的*path*、文件名或两者都超过系统定义的最大长度。例如，在基于 Windows 的平台上，路径必须少于 248 个字符，文件名必须少于 260 个字符。 |
| NotSupportedException | 档案在*path*在字符串中间包含一个冒号 (:)。 |

### 评论

此构造函数不解压缩。看[`Extract`](../extract)解压方法.

### 例子

```csharp
using (FileStream extractedFile = File.Open(extractedFileName, FileMode.Create))
{
    using (var archive = new SnappyArchive(sourceSnappyFile))
    {
         archive.Extract(extractedFile);
    }
   }
```

### 也可以看看

* class [SnappyArchive](../../snappyarchive)
* 命名空间 [Aspose.Zip.Snappy](../../snappyarchive)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
