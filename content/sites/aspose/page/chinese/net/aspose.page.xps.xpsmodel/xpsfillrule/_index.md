---
title: XpsFillRule
second_title: Aspose.Page for .NET API 参考
description: PathGeometry 元素的 FillRule 属性的有效值
type: docs
weight: 3010
url: /zh/net/aspose.page.xps.xpsmodel/xpsfillrule/
---
## XpsFillRule enumeration

PathGeometry 元素的 FillRule 属性的有效值。

```csharp
public enum XpsFillRule
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| EvenOdd | `0` | 此规则通过在任意方向上从该点到无穷远绘制一条射线 并计算射线穿过的给定形状的段数 来确定画布上一个点的“内部”。如果这个数是奇数，点是 里面；如果是偶数，则该点在外面。 |
| NonZero | `1` | 此规则通过在任意方向上从该点到无穷远绘制一条射线 ，然后检查形状的一部分与射线相交的位置 ，来确定画布上一个点的“内部”。从 0 开始，每次一个线段从左到右穿过射线时加一个 ，每次从右到左穿过射线的路径段减去一个 。计算交叉点后， 如果结果为零，则该点在路径之外；否则，它在里面。 |

### 也可以看看

* 命名空间 [Aspose.Page.XPS.XpsModel](../../aspose.page.xps.xpsmodel)
* 部件 [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
