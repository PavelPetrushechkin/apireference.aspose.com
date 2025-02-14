---
title: Extract
second_title: Aspose.ZIP for .NET API 参考
description: 通过提供的路径将条目提取到文件系统
type: docs
weight: 20
url: /zh/net/aspose.zip.wim/wimfileentry/extract/
---
## Extract(string) {#extract}

通过提供的路径将条目提取到文件系统。

```csharp
public FileSystemInfo Extract(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 目标文件的路径。如果文件已经存在，它将被覆盖。 |

### 返回值

组合文件的文件信息。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *path*一片空白。 |
| SecurityException | 调用者没有所需的访问权限。 |
| ArgumentException | 这*path*为空、仅包含空格或包含无效字符。 |
| UnauthorizedAccessException | 访问文件*path*被拒绝。 |
| PathTooLongException | 指定的*path*、文件名或两者都超过系统定义的最大长度。例如，在基于 Windows 的平台上，路径必须少于 248 个字符，文件名必须少于 260 个字符。 |
| NotSupportedException | 档案在*path*在字符串中间包含一个冒号 (:)。 |

### 例子

```csharp
using (var archive = new WimArchive("archive.wim"))
{
    archive.Images[0].RootDirectory.Files[0].Extract("data.bin");
}
```

### 也可以看看

* class [WimFileEntry](../../wimfileentry)
* 命名空间 [Aspose.Zip.Wim](../../wimfileentry)
* 部件 [Aspose.Zip](../../../)

---

## Extract(Stream) {#extract_1}

将条目提取到提供的流中。

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

提取 wim 存档的条目。

```csharp
using (var archive = new WimArchive("archive.wim"))
{
    archive.Images[0].RootDirectory.Files[0].Extract(httpResponseStream);
}
```

### 也可以看看

* class [WimFileEntry](../../wimfileentry)
* 命名空间 [Aspose.Zip.Wim](../../wimfileentry)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
