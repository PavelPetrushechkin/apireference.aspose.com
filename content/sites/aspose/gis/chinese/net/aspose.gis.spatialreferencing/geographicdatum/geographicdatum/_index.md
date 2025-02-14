---
title: GeographicDatum
second_title: Aspose.GIS for .NET API 参考
description: 创建新实例
type: docs
weight: 10
url: /zh/net/aspose.gis.spatialreferencing/geographicdatum/geographicdatum/
---
## GeographicDatum constructor

创建新实例。

```csharp
public GeographicDatum(string name, Ellipsoid ellipsoid, 
    BursaWolfParameters toWgs84Parameters = null, Identifier identifier = null)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 此数据的名称。 |
| ellipsoid | Ellipsoid | 该基准面的椭球体。不能为空。 |
| toWgs84Parameters | BursaWolfParameters | 参数，可提供给 bursa wolf 公式，用于将此基准中的坐标转换为 WGS84 基准中的坐标。 如果此基准接近 WGS84 并且不需要转换，则传递 bursa wolf 参数，所有值都设置为 0。 如果null，ToWgs84 将被设置为[`IsNull`](../../bursawolfparameters/isnull)参数. |
| identifier | Identifier | 此数据的标识符。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | ellipsoid一片空白。 |

### 也可以看看

* class [Ellipsoid](../../ellipsoid)
* class [BursaWolfParameters](../../bursawolfparameters)
* class [Identifier](../../identifier)
* class [GeographicDatum](../../geographicdatum)
* 命名空间 [Aspose.Gis.SpatialReferencing](../../geographicdatum)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
