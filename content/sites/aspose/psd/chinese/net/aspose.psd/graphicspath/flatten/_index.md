---
title: Flatten
second_title: Aspose.PSD for .NET API 参考
description: 将此路径中的每条曲线转换为一系列相连的线段
type: docs
weight: 90
url: /zh/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

将此路径中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten()
```

### 也可以看看

* class [GraphicsPath](../../graphicspath)
* 命名空间 [Aspose.PSD](../../graphicspath)
* 部件 [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

应用指定的变换，然后转换此曲线中的每条曲线[`GraphicsPath`](../../graphicspath)成一系列连接的线段。

```csharp
public void Flatten(Matrix matrix)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 一个[`Matrix`](../../matrix)通过它来改变这个[`GraphicsPath`](../../graphicspath)压扁之前。 |

### 也可以看看

* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* 命名空间 [Aspose.PSD](../../graphicspath)
* 部件 [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

转换此曲线中的每条曲线[`GraphicsPath`](../../graphicspath)成一系列连接的线段。

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 一个[`Matrix`](../../matrix)通过它来改变这个[`GraphicsPath`](../../graphicspath)压扁之前。 |
| flatness | Single | 指定曲线与其展平近似值之间的最大允许误差。默认值为 0.25。减小平坦度值将增加近似中的线段数。 |

### 也可以看看

* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* 命名空间 [Aspose.PSD](../../graphicspath)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
