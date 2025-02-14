---
title: SheetColorHighlightEnum
second_title: Справочник по Aspose.PSD для .NET API
description: Возможные цвета настройки цвета листа. Это декоративный цвет пользовательского интерфейса слоя в списке слоев в PS
type: docs
weight: 2940
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Возможные цвета настройки цвета листа. Это декоративный цвет пользовательского интерфейса слоя в списке слоев в PS

```csharp
public enum SheetColorHighlightEnum : short
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| NoColor | `0` | Цвет не указан. |
| Red | `1` | Красный цвет. |
| Orange | `2` | Оранжевый цвет. |
| Yellow | `3` | Желтый цвет. |
| Green | `4` | Зеленый цвет. |
| Blue | `5` | Синий цвет. |
| Violet | `6` | Фиолетовый цвет. |
| Gray | `7` | Серый цвет. |

### Примеры

В следующем примере показано, как можно изменить выделение цветом листа в Aspose.PSD (настройка цвета листа).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// В файле цвета выделения слоев идут в таком порядке
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Цвет листа слоя используется для визуального выделения слоев. 
// Например, вы можете обновить некоторые слои в PSD, а затем выделить цветом слой, который вы хотите привлечь внимание.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Цвета должны быть инвертированы
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // Ресурс lcrl всегда присутствует в списке ресурсов файла psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Инверсия цветов таблицы стилей. Настройка выделения цветом слоя.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
