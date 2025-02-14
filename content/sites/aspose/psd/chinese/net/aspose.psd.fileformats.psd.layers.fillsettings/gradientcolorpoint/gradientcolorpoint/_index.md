---
title: GradientColorPoint
second_title: Aspose.PSD for .NET API 参考
description: 初始化GradientColorPointaspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

初始化[`GradientColorPoint`](../../gradientcolorpoint)类.

```csharp
public GradientColorPoint()
```

### 也可以看看

* class [GradientColorPoint](../../gradientcolorpoint)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint)
* 部件 [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

初始化[`GradientColorPoint`](../../gradientcolorpoint)类.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 渐变色点。 |
| location | Int32 | 渐变色点的位置。 |
| medianPointLocation | Int32 | 中值梯度点位置。 |

### 例子

以下示例演示如何在图层中创建/编辑 GradientOverlayEffect 效果对象。

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// 创建/获取和编辑图层中的渐变叠加效果。
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // 在图层中搜索 GradientOverlayEffect。
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // 如果不存在，您可以创建一个新的 GradientOverlayEffect。
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 为效果添加一点透明度。
    gradientOverlayEffect.Opacity = 200;

    // 改变渐变效果的混合模式。
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // 获取 GradientFillSettings 对象来配置渐变叠加设置。
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // 使用两种颜色设置新的渐变。
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // 将渐变的倾斜度设置为 80 度角。
    settings.Angle = 80;

    // 将渐变效果缩放到 150%。
    settings.Scale = 150;

    // 设置渐变的类型。
    settings.GradientType = GradientType.Linear;

    // 通过将每个透明度点的不透明度设置为 100%，使渐变不透明。
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 也可以看看

* struct [Color](../../../aspose.psd/color)
* class [GradientColorPoint](../../gradientcolorpoint)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
