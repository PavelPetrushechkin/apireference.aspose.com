---
title: FromText
second_title: Aspose.GIS for .NET API 参考
description: 从其众所周知的文本表示创建几何图形
type: docs
weight: 470
url: /zh/net/aspose.gis.geometries/geometry/fromtext/
---
## FromText(string) {#fromtext}

从其众所周知的文本表示创建几何图形。

```csharp
public static IGeometry FromText(string wkt)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| wkt | String | 几何图形的众所周知的文本表示。 |

### 返回值

参数表示的几何图形。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数为空。 |
| NotSupportedException | 参数表示类型不受支持的几何图形。 |
| FormatException | 参数不是有效的知名文本。 |

### 也可以看看

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.Gis.Geometries](../../geometry)
* 部件 [Aspose.GIS](../../../)

---

## FromText(string, SpatialReferenceSystem) {#fromtext_1}

从其众所周知的文本表示创建几何图形。

```csharp
public static IGeometry FromText(string wkt, SpatialReferenceSystem spatialReferenceSystem)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| wkt | String | 几何图形的众所周知的文本表示。 |
| spatialReferenceSystem | SpatialReferenceSystem | 分配给几何的空间参考系统。 |

### 返回值

参数表示的几何图形。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数为空。 |
| NotSupportedException | 参数表示类型不受支持的几何图形。 |
| FormatException | 参数不是有效的知名文本。 |

### 也可以看看

* interface [IGeometry](../../igeometry)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.Gis.Geometries](../../geometry)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
