---
title: Crosses
second_title: Aspose.GIS for .NET API 参考
description: 确定此几何图形和指定几何图形是否交叉
type: docs
weight: 160
url: /zh/net/aspose.gis.geometries/igeometry/crosses/
---
## IGeometry.Crosses method

确定此几何图形和指定几何图形是否交叉。

```csharp
public bool Crosses(IGeometry other)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | IGeometry | 几何。 |

### 返回值

`true`如果这个几何“空间交叉”另一个几何。`false`否则。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 论据是`null`. |
| ArgumentException | 其中一个几何图形无效，操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)几何图形不等价。 您可以使用[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation)为了将几何图形转换为相同的 spatial 参考系统。 |

### 评论

此方法根据 DE-9IM 相交矩阵测试几何是否交叉。 两个几何如果它们有一些但不是所有的内部点共有并且 相交的维度小于至少一个的维度geometries. 即：两个[`LineString`](../../linestring) 交叉，如果它们形成一个“X”字母、一个 LineString 和一个[`Polygon`](../../polygon) 如果 LineString 穿过多边形内部，则交叉。 有关 DE-9IM 和“空间交叉”关系的更多详细信息，请参阅 OpenGIS 简单功能规范。

### 也可以看看

* interface [IGeometry](../../igeometry)
* 命名空间 [Aspose.Gis.Geometries](../../igeometry)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
