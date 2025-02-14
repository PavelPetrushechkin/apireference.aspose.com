---
title: AddOuterGlow
second_title: Справочник по Aspose.PSD для .NET API
description: Добавляет эффект внешнего свечения.
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Добавляет эффект внешнего свечения.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Возвращаемое значение

Создано[`OuterGlowEffect`](../../outergloweffect) объект

### Примеры

Следующий код демонстрирует поддержку OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Смотрите также

* class [OuterGlowEffect](../../outergloweffect)
* class [BlendingOptions](../../blendingoptions)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
