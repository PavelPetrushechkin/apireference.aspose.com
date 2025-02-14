---
title: IGeometryCollection
second_title: Aspose.GIS for .NET API 参考
description: 一个IGeometryCollection./igeometrycollection是一个IGeometry./igeometry这是一个或多个几何图形的集合
type: docs
weight: 910
url: /zh/net/aspose.gis.geometries/igeometrycollection/
---
## IGeometryCollection interface

一个[`IGeometryCollection`](../igeometrycollection)是一个[`IGeometry`](../igeometry)这是一个或多个几何图形的集合。

```csharp
public interface IGeometryCollection : IEnumerable<IGeometry>, IEquatable<IGeometryCollection>, 
    IGeometry
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.geometries/igeometrycollection/count) { get; } | 获取此集合中的几何图形数。 |
| [Item](../../aspose.gis.geometries/igeometrycollection/item) { get; } | 得到一个[`IGeometry`](../igeometry)在指定的索引处。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetPointOnSurface](../../aspose.gis.geometries/igeometrycollection/getpointonsurface)() | 找到一个保证在此集合中的一个表面上的点。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometrycollection/replacepolygonsbylines)() | 获取表示为此几何的线的多边形。 |
| [ToEditable](../../aspose.gis.geometries/igeometrycollection/toeditable)() | 获取此几何图形的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry#tolineargeometry)() | 使用默认值获取此几何图形的近似或等效非曲线版本`宽容`. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry#tolineargeometry_1)(double) | 使用指定的获取此几何图形的近似或等效非曲线版本`宽容`. |

### 也可以看看

* interface [IGeometry](../igeometry)
* 命名空间 [Aspose.Gis.Geometries](../../aspose.gis.geometries)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
