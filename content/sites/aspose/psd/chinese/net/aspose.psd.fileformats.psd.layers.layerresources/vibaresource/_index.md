---
title: VibAResource
second_title: Aspose.PSD for .NET API 参考
description: VibA 资源.
type: docs
weight: 3290
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

VibA 资源.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VibAResource](vibaresource)() | 初始化[`VibAResource`](../vibaresource)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length) { get; } | 获取层资源长度（以字节为单位）。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion) { get; } | 获取psd版本。 |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation) { get; set; } | 获取或设置饱和值 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | 获取签名。 |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance) { get; set; } | 获取或设置振动值 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save)(StreamContainer, int) | 将资源保存到指定的流容器。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | 返回一个String代表这个实例。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey) | 类型工具信息键。 |

### 例子

下面的代码示例演示了对 VibAResource 资源的支持。

```csharp
[C#]

// 运行时支持读写振动资源的示例。
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 也可以看看

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
