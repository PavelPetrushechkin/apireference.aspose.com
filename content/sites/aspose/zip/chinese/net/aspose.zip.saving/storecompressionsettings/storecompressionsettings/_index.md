---
title: StoreCompressionSettings
second_title: Aspose.ZIP for .NET API 参考
description: 初始化StoreCompressionSettingsaspose.zip.saving/storecompressionsettings类.
type: docs
weight: 10
url: /zh/net/aspose.zip.saving/storecompressionsettings/storecompressionsettings/
---
## StoreCompressionSettings constructor

初始化[`StoreCompressionSettings`](../../storecompressionsettings)类.

```csharp
public StoreCompressionSettings()
```

### 例子

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new StoreCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");                   
    archive.Save(zipFile);
}
```

### 也可以看看

* class [StoreCompressionSettings](../../storecompressionsettings)
* 命名空间 [Aspose.Zip.Saving](../../storecompressionsettings)
* 部件 [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
