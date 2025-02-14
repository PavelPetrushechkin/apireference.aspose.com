---
title: Extent
second_title: Aspose.GIS for .NET API 参考
description: 指定要渲染的地图边界 如果设置为null 在渲染期间计算范围以包括所有图层中的所有几何图形
type: docs
weight: 40
url: /zh/net/aspose.gis.rendering/map/extent/
---
## Map.Extent property

指定要渲染的地图边界。 如果设置为`null` 在渲染期间计算范围以包括所有图层中的所有几何图形。

```csharp
public Extent Extent { get; set; }
```

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | [`IsValid`](../../../aspose.gis/extent/isvalid)是`false`.[`Width`](../../../aspose.gis/extent/width)小于或等于零。[`Height`](../../../aspose.gis/extent/height)小于或等于零。[`SpatialReferenceSystem`](../../../aspose.gis/extent/spatialreferencesystem)是`null`. |

### 评论

如果范围的空间参考系统不等于地图的空间参考系统，则在渲染期间将范围转换 到目标空间参考系统。

### 也可以看看

* class [Extent](../../../aspose.gis/extent)
* class [Map](../../map)
* 命名空间 [Aspose.Gis.Rendering](../../map)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
