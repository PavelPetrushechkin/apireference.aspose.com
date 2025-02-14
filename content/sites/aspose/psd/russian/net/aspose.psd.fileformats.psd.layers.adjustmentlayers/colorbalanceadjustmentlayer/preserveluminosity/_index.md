---
title: PreserveLuminosity
second_title: Справочник по Aspose.PSD для .NET API
description: Получает или задает значение указывающее является ли этоBlncResourceaspose.psd.fileformats.psd.layers.layerresources/blncresource сохраняет яркость.
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Получает или задает значение, указывающее, является ли это[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource) сохраняет яркость.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Стоимость имущества

`истинный` если он сохраняет светимость; в противном случае,`ЛОЖЬ` .

### Примеры

Следующий код демонстрирует поддержку ColorBalanceAdjustmentLayer.

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### Смотрите также

* class [ColorBalanceAdjustmentLayer](../../colorbalanceadjustmentlayer)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
