---
title: Item
second_title: Aspose.GIS for .NET API 参考
description: 获取或设置FeatureAttributeaspose.gis/featureattribute在指定的索引处
type: docs
weight: 30
url: /zh/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

获取或设置[`FeatureAttribute`](../../featureattribute)在指定的索引处。

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| 范围 | 描述 |
| --- | --- |
| index | 要获取或设置的属性的从零开始的索引。 |

### 返回值

指定索引处的属性。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 索引超出范围。 |
| InvalidOperationException | 尝试修改锁定的集合。 |

### 也可以看看

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* 命名空间 [Aspose.Gis](../../featureattributecollection)
* 部件 [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

获取或设置[`FeatureAttribute`](../../featureattribute)具有指定的名称。

```csharp
public FeatureAttribute this[string name] { get; }
```

| 范围 | 描述 |
| --- | --- |
| name | 属性的名称。 |

### 返回值

具有指定名称的属性，或`null`如果没有找到。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 属性名称是`null`. |

### 也可以看看

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* 命名空间 [Aspose.Gis](../../featureattributecollection)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
