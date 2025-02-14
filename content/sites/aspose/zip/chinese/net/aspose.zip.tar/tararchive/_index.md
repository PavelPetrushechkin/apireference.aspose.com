---
title: TarArchive
second_title: Aspose.ZIP for .NET API 参考
description: 这个类代表 tar 归档文件使用它来编写提取或更新 tar 档案
type: docs
weight: 600
url: /zh/net/aspose.zip.tar/tararchive/
---
## TarArchive class

这个类代表 tar 归档文件。使用它来编写、提取或更新 tar 档案。

```csharp
public class TarArchive : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TarArchive](tararchive#constructor)() | 初始化[`TarArchive`](../tararchive)类. |
| [TarArchive](tararchive#constructor_1)(Stream) | 初始化[`Archive`](../../aspose.zip/archive)可以从存档中提取类和组成条目列表。 |
| [TarArchive](tararchive#constructor_2)(string) | 初始化[`TarArchive`](../tararchive)可以从存档中提取类和组成条目列表。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Entries](../../aspose.zip.tar/tararchive/entries) { get; } | 获取条目[`TarEntry`](../tarentry)构成档案的类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromGZip](../../aspose.zip.tar/tararchive/fromgzip#fromgzip)(Stream) | 提取提供的 gzip 存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromGZip](../../aspose.zip.tar/tararchive/fromgzip#fromgzip_1)(string) | 提取提供的 gzip 存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromLZip](../../aspose.zip.tar/tararchive/fromlzip#fromlzip)(Stream) | 提取提供的 lzip 存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromLZip](../../aspose.zip.tar/tararchive/fromlzip#fromlzip_1)(string) | 提取提供的 lzip 存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromXz](../../aspose.zip.tar/tararchive/fromxz#fromxz)(Stream) | 提取提供的 xz 格式存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromXz](../../aspose.zip.tar/tararchive/fromxz#fromxz_1)(string) | 提取提供的 xz 格式存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromZ](../../aspose.zip.tar/tararchive/fromz#fromz)(Stream) | 提取提供的 Z 格式存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| static [FromZ](../../aspose.zip.tar/tararchive/fromz#fromz_1)(string) | 提取提供的 Z 格式存档并组成[`TarArchive`](../tararchive)从提取的数据中。 |
| [CreateEntries](../../aspose.zip.tar/tararchive/createentries#createentries)(DirectoryInfo, bool) | 将给定目录中的所有文件和目录递归添加到存档中。 |
| [CreateEntries](../../aspose.zip.tar/tararchive/createentries#createentries_1)(string, bool) | 将给定目录中的所有文件和目录递归添加到存档中。 |
| [CreateEntry](../../aspose.zip.tar/tararchive/createentry#createentry)(string, FileInfo, bool) | 在存档中创建单个条目。 |
| [CreateEntry](../../aspose.zip.tar/tararchive/createentry#createentry_1)(string, Stream, FileSystemInfo) | 在存档中创建单个条目。 |
| [CreateEntry](../../aspose.zip.tar/tararchive/createentry#createentry_2)(string, string, bool) | 在存档中创建单个条目。 |
| [DeleteEntry](../../aspose.zip.tar/tararchive/deleteentry#deleteentry_1)(int) | 按索引从条目列表中删除条目。 |
| [DeleteEntry](../../aspose.zip.tar/tararchive/deleteentry#deleteentry)(TarEntry) | 从条目列表中删除特定条目的第一个匹配项。 |
| [Dispose](../../aspose.zip.tar/tararchive/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [ExtractToDirectory](../../aspose.zip.tar/tararchive/extracttodirectory)(string) | 将存档中的所有文件提取到提供的目录。 |
| [Save](../../aspose.zip.tar/tararchive/save#save)(Stream, TarFormat?) | 将存档保存到提供的流中。 |
| [Save](../../aspose.zip.tar/tararchive/save#save_1)(string, TarFormat?) | 将存档保存到提供的目标文件。 |
| [SaveGzipped](../../aspose.zip.tar/tararchive/savegzipped#savegzipped)(Stream, TarFormat?) | 使用 gzip 压缩将存档保存到流中。 |
| [SaveGzipped](../../aspose.zip.tar/tararchive/savegzipped#savegzipped_1)(string, TarFormat?) | 使用 gzip 压缩按路径将存档保存到文件中。 |
| [SaveLzipped](../../aspose.zip.tar/tararchive/savelzipped#savelzipped)(Stream, TarFormat?) | 使用 lzip 压缩将存档保存到流中。 |
| [SaveLzipped](../../aspose.zip.tar/tararchive/savelzipped#savelzipped_1)(string, TarFormat?) | 使用 lzip 压缩按路径将存档保存到文件中。 |
| [SaveXzCompressed](../../aspose.zip.tar/tararchive/savexzcompressed#savexzcompressed)(Stream, TarFormat?, XzArchiveSettings) | 使用 xz 压缩将存档保存到流中。 |
| [SaveXzCompressed](../../aspose.zip.tar/tararchive/savexzcompressed#savexzcompressed_1)(string, TarFormat?, XzArchiveSettings) | 使用 xz 压缩按路径将存档保存到路径。 |
| [SaveZCompressed](../../aspose.zip.tar/tararchive/savezcompressed#savezcompressed)(Stream, TarFormat?) | 使用 Z 压缩将存档保存到流中。 |
| [SaveZCompressed](../../aspose.zip.tar/tararchive/savezcompressed#savezcompressed_1)(string, TarFormat?) | 使用 Z 压缩按路径将存档保存到路径。 |

### 也可以看看

* 命名空间 [Aspose.Zip.Tar](../../aspose.zip.tar)
* 部件 [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
