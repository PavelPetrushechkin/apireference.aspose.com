---
title: GraphicContext
second_title: Aspose.SVG for .NET API 参考
description: 保存当前的图形控制参数 这些参数定义了图形操作符执行的全局框架
type: docs
weight: 2760
url: /zh/net/aspose.svg.rendering/graphiccontext/
---
## GraphicContext class

保存当前的图形控制参数。 这些参数定义了图形操作符执行的全局框架。

```csharp
public class GraphicContext : ICloneable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](graphiccontext)() | 初始化[`GraphicContext`](../graphiccontext)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing) { get; set; } | 设置或获取字符间距。 |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush) { get; set; } | 设置或获取用于填充路径内部的画笔对象。 |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font) { get; set; } | 设置或获取用于渲染文本的真字体对象。 |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize) { get; set; } | 设置或获取文本字体大小。 |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle) { get; set; } | 设置或获取文本字体样式。 |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap) { get; set; } | 设置或获取指定任何被描边的开放路径的端点形状的代码。 |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset) { get; set; } | 设置或获取当前虚线图案的相位偏移。 |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern) { get; set; } | 设置或获取描边路径时要使用的虚线模式的描述。 |
| virtual [LineDashStyle](../../aspose.svg.rendering/graphiccontext/linedashstyle) { get; set; } | 获取描边路径的虚线样式。 |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin) { get; set; } | 设置或获取指定描边路径的连接段之间的关节形状的代码。 |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth) { get; set; } | 设置或获取要描边的路径的粗细。 |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit) { get; set; } | 设置或获取描边路径的斜接线连接的最大长度。 此参数限制线段以锐角连接时产生的“尖峰”长度。 |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush) { get; set; } | 设置或获取用于描边路径的画笔对象。 |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo) { get; } | 得到一个[`TextInfo`](../textinfo)包含有关渲染文本信息的对象。 |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix) { get; set; } | 设置或获取变换矩阵。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone)() | 创建一个具有与现有实例相同属性值的 GraphicContext 类的新实例。 |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform)(Matrix) | 通过乘以指定矩阵来修改当前变换矩阵。 |

### 也可以看看

* 命名空间 [Aspose.Svg.Rendering](../../aspose.svg.rendering)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
