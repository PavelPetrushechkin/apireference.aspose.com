---
title: SupportsSpatialReferenceSystem
second_title: Aspose.GIS for .NET API 参考
description: 确定驱动程序是否支持指定的空间参考系统
type: docs
weight: 100
url: /zh/net/aspose.gis/filedriver/supportsspatialreferencesystem/
---
## FileDriver.SupportsSpatialReferenceSystem method

确定驱动程序是否支持指定的空间参考系统。

```csharp
public abstract bool SupportsSpatialReferenceSystem(SpatialReferenceSystem spatialReferenceSystem)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

布尔值，表示驱动程序是否支持指定的空间参考系统。 `null`被认为被任何驱动程序支持。

### 评论

如果不支持空间参考系统，则将其传递给[`CreateLayer`](../createlayer)方法， aNotSupportedException将被抛出。

### 也可以看看

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [FileDriver](../../filedriver)
* 命名空间 [Aspose.Gis](../../filedriver)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
