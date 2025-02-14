---
title: CreateEntries
second_title: Aspose.ZIP for .NET API 参考
description: 将给定目录中的所有文件和目录递归添加到存档中
type: docs
weight: 40
url: /zh/net/aspose.zip.sevenzip/sevenziparchive/createentries/
---
## CreateEntries(DirectoryInfo, bool) {#createentries}

将给定目录中的所有文件和目录递归添加到存档中。

```csharp
public SevenZipArchive CreateEntries(DirectoryInfo directory, bool includeRootDirectory = true)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| directory | DirectoryInfo | 要压缩的目录。 |
| includeRootDirectory | Boolean | 指示是否包含根目录本身。 |

### 返回值

包含条目的存档。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| DirectoryNotFoundException | 通往的道路*directory*无效，例如位于未映射的驱动器上。 |
| SecurityException | 调用者没有所需的访问权限*directory*. |

### 例子

```csharp
using (SevenZipArchive archive = new SevenZipArchive())
{
    DirectoryInfo folder = new DirectoryInfo("C:\folder");
    archive.CreateEntries(folder);
    archive.Save("folder.7z");
}
```

### 也可以看看

* class [SevenZipArchive](../../sevenziparchive)
* 命名空间 [Aspose.Zip.SevenZip](../../sevenziparchive)
* 部件 [Aspose.Zip](../../../)

---

## CreateEntries(string, bool) {#createentries_1}

将给定目录中的所有文件和目录递归添加到存档中。

```csharp
public SevenZipArchive CreateEntries(string sourceDirectory, bool includeRootDirectory = true)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sourceDirectory | String | 要压缩的目录。 |
| includeRootDirectory | Boolean | 指示是否包含根目录本身。 |

### 返回值

包含条目的存档。

### 例子

使用 LZMA2 压缩编写 7z 存档。

```csharp
using (SevenZipArchive archive = new SevenZipArchive(new SevenZipEntrySettings(new SevenZipLZMACompressionSettings())))
{
    archive.CreateEntries("C:\folder");
    archive.Save("folder.7z");
}
```

### 也可以看看

* class [SevenZipArchive](../../sevenziparchive)
* 命名空间 [Aspose.Zip.SevenZip](../../sevenziparchive)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
