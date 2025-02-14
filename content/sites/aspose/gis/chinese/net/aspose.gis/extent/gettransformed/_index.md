---
title: GetTransformed
second_title: Aspose.GIS for .NET API 参考
description: 返回指定范围内的新范围SpatialReferenceSystemaspose.gis.spatialreferencing/spatialreferencesystem包含此范围
type: docs
weight: 150
url: /zh/net/aspose.gis/extent/gettransformed/
---
## Extent.GetTransformed method

返回指定范围内的新范围[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem)包含此范围。

```csharp
public Extent GetTransformed(SpatialReferenceSystem targetSrs)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem)转变为。 |

### 返回值

将此范围转换为指定 SRS 的结果。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 论据是`null`. |
| NotSupportedException | 不支持转换为提供的 SRS。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception) | 转型失败。 |
| InvalidOperationException | [`SpatialReferenceSystem`](../spatialreferencesystem)这种程度是`null`. |

### 也可以看看

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [Extent](../../extent)
* 命名空间 [Aspose.Gis](../../extent)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
