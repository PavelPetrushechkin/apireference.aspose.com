---
title: PathBuilder
second_title: Aspose.SVG for .NET API 参考
description: PathBuilder 类负责构建路径段SVGPathSeg../aspose.svg.paths/svgpathseg来自跟踪点列表
type: docs
weight: 2150
url: /zh/net/aspose.svg.imagevectorization/pathbuilder/
---
## PathBuilder class

PathBuilder 类负责构建路径段[`SVGPathSeg`](../../aspose.svg.paths/svgpathseg)来自跟踪点列表。

```csharp
public class PathBuilder : IPathBuilder
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathBuilder](pathbuilder#constructor)() | 初始化[`PathBuilder`](../pathbuilder)类. |
| [PathBuilder](pathbuilder#constructor_1)(float) | 初始化[`PathBuilder`](../pathbuilder)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/pathbuilder/tension) { get; set; } | 张力值会影响曲线在（插值）控制点处弯曲的剧烈程度。 它必须在 0 到 1 的范围内。任何更高或更低的值都将与该范围的最小值和最大值对齐，因此. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/pathbuilder/build)(IEnumerable&lt;PointF&gt;, SVGPathElement) | 从跟踪点列表构建路径段。 |

### 也可以看看

* interface [IPathBuilder](../ipathbuilder)
* 命名空间 [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
