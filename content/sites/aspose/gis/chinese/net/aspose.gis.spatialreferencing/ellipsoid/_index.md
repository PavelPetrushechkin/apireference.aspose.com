---
title: Ellipsoid
second_title: Aspose.GIS for .NET API 参考
description: Ellipsoid 表示一个椭球体它近似于地球
type: docs
weight: 1970
url: /zh/net/aspose.gis.spatialreferencing/ellipsoid/
---
## Ellipsoid class

Ellipsoid 表示一个椭球体，它近似于地球。

```csharp
public class Ellipsoid : IdentifiableObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Ellipsoid](ellipsoid)(string, double, double, Identifier) | 创建新的椭球体。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Airy](../../aspose.gis.spatialreferencing/ellipsoid/airy) { get; } | 艾里椭球体. |
| static [Grs80](../../aspose.gis.spatialreferencing/ellipsoid/grs80) { get; } | GRS 1980 椭球体. |
| static [Wgs72](../../aspose.gis.spatialreferencing/ellipsoid/wgs72) { get; } | WGS 72 椭球体. |
| static [Wgs84](../../aspose.gis.spatialreferencing/ellipsoid/wgs84) { get; } | WGS 84 椭球体. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode) { get; } | 如果此对象标识符是 EPSG 标识符 - 返回其代码。否则 - 返回 -1. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier) { get; } | 此可识别对象的标识符。 |
| [InverseFlattening](../../aspose.gis.spatialreferencing/ellipsoid/inverseflattening) { get; } | 椭球的逆展平。如果这是一个球体，则为 0。 |
| [IsSphere](../../aspose.gis.spatialreferencing/ellipsoid/issphere) { get; } | 检测此椭球是否为球体。 |
| [IsValid](../../aspose.gis.spatialreferencing/ellipsoid/isvalid) { get; } | 检测椭球是否有效：其半长轴大于 0，反展平为正或等于 0。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name) { get; } | 此对象的名称。 |
| [SemiMajorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semimajoraxis) { get; } | 椭球的半长轴。 |
| [SemiMinorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semiminoraxis) { get; } | 椭球的半短轴。如果这是一个球体，则等于半长轴。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent)(Ellipsoid) | 确定两个椭球是否等价。 如果椭球 A 等价于椭球 B，则它们具有相同的半长轴和反向展平。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring)() | 返回表示当前对象的字符串。 |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent)(Ellipsoid, Ellipsoid) | 确定两个椭球是否等价。 如果椭球 A 等价于椭球 B，则它们具有相同的半长轴和反向展平。 |

### 也可以看看

* class [IdentifiableObject](../identifiableobject)
* 命名空间 [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
