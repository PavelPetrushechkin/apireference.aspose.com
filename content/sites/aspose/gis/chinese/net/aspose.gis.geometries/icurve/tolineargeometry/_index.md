---
title: ToLinearGeometry
second_title: Aspose.GIS for .NET API 参考
description: 使用默认值获取此几何图形的近似或等效非曲线版本宽容.
type: docs
weight: 50
url: /zh/net/aspose.gis.geometries/icurve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

使用默认值获取此几何图形的近似或等效非曲线版本`宽容`.

```csharp
public ILineString ToLinearGeometry()
```

### 返回值

一个[`ILineString`](../../ilinestring)近似或等价于这条曲线。 这等价于[`ToLinearGeometry`](../tolineargeometry)with 默认`宽容`.默认`宽容` 值取决于[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem)这个几何的 ： 对于预计的 SRS 公差为 0.001 米（以 SRS 为单位）对于地理 SRS 容差为`1e-5`度（以 SRS 为单位）对于未知的 SRS 公差是`1e-5` 有关应用哪些转换的更多详细信息，请参阅[`ToLinearGeometry`](../tolineargeometry)规格.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 这个几何图形无效，操作无法完成。 |

### 也可以看看

* interface [ILineString](../../ilinestring)
* interface [ICurve](../../icurve)
* 命名空间 [Aspose.Gis.Geometries](../../icurve)
* 部件 [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

使用指定的获取此几何图形的近似或等效非曲线版本`宽容`.

```csharp
public ILineString ToLinearGeometry(double tolerance)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tolerance | Double | 的`宽容`使用。结果保证小于`宽容`远离 弯曲几何，除非线性化几何所需的点数超过每象限最大值， 当前等于10000点。 |

### 返回值

一个[`ILineString`](../../ilinestring)近似或等效于这条曲线：  如果这个对象是[`ILineString`](../../ilinestring)本身结果等价于这个对象 如果这个对象是[`ICircularString`](../../icircularstring)结果是用指定的线性化的圆形字符串*tolerance* 如果这个对象是[`ICompoundCurve`](../../icompoundcurve) 来自它的所有曲线都被线性化，然后加入[`ILineString`](../../ilinestring)

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | `宽容`小于或等于`0`. |
| InvalidOperationException | 这个几何图形无效，操作无法完成。 |

### 也可以看看

* interface [ILineString](../../ilinestring)
* interface [ICurve](../../icurve)
* 命名空间 [Aspose.Gis.Geometries](../../icurve)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
