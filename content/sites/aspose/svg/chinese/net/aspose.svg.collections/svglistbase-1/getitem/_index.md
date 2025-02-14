---
title: GetItem
second_title: Aspose.SVG for .NET API 参考
description: 从列表中返回指定的项目
type: docs
weight: 70
url: /zh/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

从列表中返回指定的项目。

```csharp
public T GetItem(ulong index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | UInt64 | 列表中要返回的项目的索引。第一项是数字 0。 |

### 返回值

选定的项目。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | 代码[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err). 如果索引号大于或等于 numberOfItems 则引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../../svglistbase-1)
* 命名空间 [Aspose.Svg.Collections](../../svglistbase-1)
* 部件 [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
