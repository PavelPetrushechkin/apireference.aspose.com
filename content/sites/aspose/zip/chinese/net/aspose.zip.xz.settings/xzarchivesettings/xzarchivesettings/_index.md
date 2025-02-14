---
title: XzArchiveSettings
second_title: Aspose.ZIP for .NET API 参考
description: 初始化XzArchiveSettingsaspose.zip.xz.settings/xzarchivesettings使用单个 LZMA2 压缩的类
type: docs
weight: 10
url: /zh/net/aspose.zip.xz.settings/xzarchivesettings/xzarchivesettings/
---
## XzArchiveSettings() {#constructor}

初始化[`XzArchiveSettings`](../../xzarchivesettings)使用单个 LZMA2 压缩的类。

```csharp
public XzArchiveSettings()
```

### 评论

LZMA2过滤器中的默认字典大小等于16兆字节，默认块大小等于64兆字节，默认校验和类型是CRC32.

### 也可以看看

* class [XzArchiveSettings](../../xzarchivesettings)
* 命名空间 [Aspose.Zip.Xz.Settings](../../xzarchivesettings)
* 部件 [Aspose.Zip](../../../)

---

## XzArchiveSettings(XzFilterSettings[], long, XzCheckType) {#constructor_1}

初始化[`XzArchiveSettings`](../../xzarchivesettings)具有自定义参数的类。

```csharp
public XzArchiveSettings(XzFilterSettings[] filters, long blockSize, XzCheckType checkType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filters | XzFilterSettings[] | 要顺序应用的过滤器（压缩器）以创建[`XzArchive`](../../../aspose.zip.xz/xzarchive).它可以是单一的[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings) 或一对[`XzBcjX86FilterSettings`](../../xzbcjx86filtersettings)和[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings) |
| blockSize | Int64 | 大小 xz 存档块。 |
| checkType | XzCheckType | 未压缩数据的校验和计算类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *blockSize*是负数。 |
| ArgumentNullException | *filters*一片空白 |
| ArgumentException | *filters*有少于一个或多于两个过滤器，或者最后一个过滤器不是[`XzLZMA2FilterSettings`](../../xzlzma2filtersettings). |

### 例子

```csharp
using (FileStream xzFile = File.Open("archive.xz", FileMode.Create))
{
    XzLZMA2FilterSettings filter = new XzLZMA2FilterSettings(5242880);
    XzArchiveSettings settings = new XzArchiveSettings(new XzFilterSettings[] {filter}, 10485760, XzCheckType.Crc32);
    using (var archive = new XzArchive(settings))
    {
        archive.SetSource("data.bin");
        archive.Save(xzFile);
     }
}
```

### 也可以看看

* class [XzFilterSettings](../../xzfiltersettings)
* enum [XzCheckType](../../xzchecktype)
* class [XzArchiveSettings](../../xzarchivesettings)
* 命名空间 [Aspose.Zip.Xz.Settings](../../xzarchivesettings)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
