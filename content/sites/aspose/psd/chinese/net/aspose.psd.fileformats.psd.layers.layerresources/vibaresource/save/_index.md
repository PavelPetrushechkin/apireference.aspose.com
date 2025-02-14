---
title: Save
second_title: Aspose.PSD for .NET API 参考
description: 将资源保存到指定的流容器
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

将资源保存到指定的流容器。

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | StreamContainer | 要保存到的流容器。 |
| psdVersion | Int32 | PSD版本。 |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer)
* class [VibAResource](../../vibaresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
