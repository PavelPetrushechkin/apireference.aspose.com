---
title: SizeF
second_title: Aspose.PSD for .NET API 参考
description: 存储一对有序的浮点数通常是矩形的宽度和高度
type: docs
weight: 5490
url: /zh/net/aspose.psd/sizef/
---
## SizeF structure

存储一对有序的浮点数，通常是矩形的宽度和高度。

```csharp
public struct SizeF
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SizeF](sizef#constructor)(PointF) | 初始化[`SizeF`](../sizef)从指定的结构[`PointF`](../pointf) . |
| [SizeF](sizef#constructor_1)(SizeF) | 初始化[`SizeF`](../sizef)从指定的结构[`SizeF`](../sizef) . |
| [SizeF](sizef#constructor_2)(float, float) | 初始化[`SizeF`](../sizef)指定尺寸的结构。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty) { get; } | 获取一个新的实例[`SizeF`](../sizef)具有的结构[`Width`](./width)和[`Height`](./height)值设置为零。 |
| [Height](../../aspose.psd/sizef/height) { get; set; } | 获取或设置 this 的垂直分量[`SizeF`](../sizef) . |
| [IsEmpty](../../aspose.psd/sizef/isempty) { get; } | 获取一个值，该值指示这是否[`SizeF`](../sizef)宽度和高度为零。 |
| [Width](../../aspose.psd/sizef/width) { get; set; } | 获取或设置 this 的水平分量[`SizeF`](../sizef) . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add)(SizeF, SizeF) | 加一的宽和高[`SizeF`](../sizef)结构到另一个的宽度和高度[`SizeF`](../sizef)结构. |
| static [Subtract](../../aspose.psd/sizef/subtract)(SizeF, SizeF) | 减去一个的宽度和高度[`SizeF`](../sizef)结构从另一个的宽度和高度[`SizeF`](../sizef)结构. |
| override [Equals](../../aspose.psd/sizef/equals)(object) | 测试指定对象是否为[`SizeF`](../sizef)与此尺寸相同[`SizeF`](../sizef) . |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode)() | 为此返回哈希码[`Size`](../size)结构. |
| [ToPointF](../../aspose.psd/sizef/topointf)() | 转换一个[`SizeF`](../sizef)到一个[`PointF`](../pointf) . |
| [ToSize](../../aspose.psd/sizef/tosize)() | 转换一个[`SizeF`](../sizef)到一个[`Size`](../size)具有截断大小值的结构。 |
| override [ToString](../../aspose.psd/sizef/tostring)() | 创建一个人类可读的字符串来表示这个[`SizeF`](../sizef) . |
| [operator +](../../aspose.psd/sizef/op_addition) | 加一的宽和高[`SizeF`](../sizef)结构到另一个的宽度和高度[`SizeF`](../sizef)结构. |
| [operator ==](../../aspose.psd/sizef/op_equality) | 测试是否两个[`SizeF`](../sizef)结构是平等的。 |
| [explicit operator](../../aspose.psd/sizef/op_explicit) | 转换指定的[`SizeF`](../sizef)到一个[`PointF`](../pointf) . |
| [operator !=](../../aspose.psd/sizef/op_inequality) | 测试是否两个[`SizeF`](../sizef)结构不同。 |
| [operator -](../../aspose.psd/sizef/op_subtraction) | 减去一个的宽度和高度[`SizeF`](../sizef)结构从另一个的宽度和高度[`SizeF`](../sizef)结构. |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
