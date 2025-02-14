---
title: Contains
second_title: Aspose.GIS for .NET API 参考
description: 确定此范围是否包含由参数定义的坐标
type: docs
weight: 120
url: /zh/net/aspose.gis/extent/contains/
---
## Contains(double, double) {#contains_2}

确定此范围是否包含由参数定义的坐标。

```csharp
public bool Contains(double x, double y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | X 的坐标。 |
| y | Double | Y 坐标。 |

### 返回值

值，表示坐标是否在边界框内。

### 评论

位于此边界上的坐标[`Extent`](../../extent)are 被认为包含于此[`Extent`](../../extent).

### 也可以看看

* class [Extent](../../extent)
* 命名空间 [Aspose.Gis](../../extent)
* 部件 [Aspose.GIS](../../../)

---

## Contains(Extent) {#contains}

确定此范围是否包含参数。

```csharp
public bool Contains(Extent extent)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extent | Extent | 另一个程度。 |

### 返回值

值，指示此范围是否包含参数。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 论据是`null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)这种程度和论点都不是`null`并且不等于彼此。 |

### 评论

位于此边界上的坐标[`Extent`](../../extent)are 被认为包含于此[`Extent`](../../extent) .出于这个原因，相等的范围被认为 相互包含。

### 也可以看看

* class [Extent](../../extent)
* 命名空间 [Aspose.Gis](../../extent)
* 部件 [Aspose.GIS](../../../)

---

## Contains(IGeometry) {#contains_1}

确定此范围是否包含参数。

```csharp
public bool Contains(IGeometry geometry)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| geometry | IGeometry | 用于测试包容性的几何图形。 |

### 返回值

值，指示此范围是否包含参数。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 论据是`null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)这种程度和论点都不是`null`并且不等于彼此。 |

### 评论

位于此边界上的坐标[`Extent`](../../extent)are 被认为包含于此[`Extent`](../../extent).

### 也可以看看

* interface [IGeometry](../../../aspose.gis.geometries/igeometry)
* class [Extent](../../extent)
* 命名空间 [Aspose.Gis](../../extent)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
