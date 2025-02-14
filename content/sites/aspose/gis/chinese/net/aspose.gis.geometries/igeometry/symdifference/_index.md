---
title: SymDifference
second_title: Aspose.GIS for .NET API 参考
description: 在此几何图形和指定几何图形之间建立对称差异
type: docs
weight: 330
url: /zh/net/aspose.gis.geometries/igeometry/symdifference/
---
## IGeometry.SymDifference method

在此几何图形和指定几何图形之间建立对称差异。

```csharp
public IGeometry SymDifference(IGeometry other)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | IGeometry | 用于计算对称差异的几何。 |

### 返回值

表示此几何和参数的对称差的几何。结果几何包含 点集，该点集存在于其中一个几何中但不存在于它们两者中。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *other*是`null`. |
| ArgumentException | 其中一个几何图形无效，操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)几何图形不等价。 您可以使用[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation)为了将几何图形转换为相同的 spatial 参考系统。 |

### 也可以看看

* interface [IGeometry](../../igeometry)
* 命名空间 [Aspose.Gis.Geometries](../../igeometry)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
