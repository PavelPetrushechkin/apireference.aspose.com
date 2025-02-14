---
title: ToLinearGeometry
second_title: Aspose.GIS for .NET API 参考
description: 使用默认值获取此几何图形的近似或等效非曲线版本宽容.
type: docs
weight: 60
url: /zh/net/aspose.gis.geometries/igeometrycollection/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

使用默认值获取此几何图形的近似或等效非曲线版本`宽容`.

```csharp
public IGeometryCollection ToLinearGeometry()
```

### 返回值

没有曲线几何图形的几何图形。这相当于[`ToLinearGeometry`](../tolineargeometry)with 默认`宽容`.默认`宽容` 值取决于[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem)这个几何的 ： 对于预计的 SRS 公差为 0.001 米（以 SRS 为单位）对于地理 SRS 容差为`1e-5`度（以 SRS 为单位）对于未知的 SRS 公差是`1e-5` 有关应用哪些转换的更多详细信息，请参阅[`ToLinearGeometry`](../tolineargeometry)规格.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 这个几何图形无效，操作无法完成。 |

### 也可以看看

* interface [IGeometryCollection](../../igeometrycollection)
* 命名空间 [Aspose.Gis.Geometries](../../igeometrycollection)
* 部件 [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

使用指定的获取此几何图形的近似或等效非曲线版本`宽容`.

```csharp
public IGeometryCollection ToLinearGeometry(double tolerance)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tolerance | Double | 的`宽容`使用。结果保证小于`宽容`远离 弯曲几何，除非线性化几何所需的点数超过每象限最大值， 当前等于10000点。 |

### 返回值

没有曲线几何图形的几何图形。应用了以下转换： CircularString 被线性化 （转化为LineString 指定*tolerance*)CompoundCurve s 加入`线串`sCurvePolygon 转换为PolygonsMultiCurve 转换为MultiCurvesMultiSurface 转换为MultiPolygons 结果，[`HasCurveGeometry`](../../igeometry/hascurvegeometry)输出几何是`false`.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | `宽容`小于或等于`0`. |
| InvalidOperationException | 这个几何图形无效，操作无法完成。 |

### 也可以看看

* interface [IGeometryCollection](../../igeometrycollection)
* 命名空间 [Aspose.Gis.Geometries](../../igeometrycollection)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
