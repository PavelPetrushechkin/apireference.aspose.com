---
title: Warp
second_title: Aspose.GIS for .NET API 参考
description: 将栅格图层扭曲到另一个图层
type: docs
weight: 210
url: /zh/net/aspose.gis.raster/rasterlayer/warp/
---
## RasterLayer.Warp method

将栅格图层扭曲到另一个图层。

```csharp
public RasterLayer Warp(WarpOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | WarpOptions | 重投影过程的选项。 |

### 返回值

扭曲栅格图层。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数不能为空。参数名称：选项。 |
| ArgumentException | 未知源空间参考系统。 |
| InvalidOperationException | 原始图层不能是另一个 WarpRasterLayer。 |

### 也可以看看

* class [WarpOptions](../../warpoptions)
* class [RasterLayer](../../rasterlayer)
* 命名空间 [Aspose.Gis.Raster](../../rasterlayer)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
