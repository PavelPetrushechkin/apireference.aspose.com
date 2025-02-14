---
title: SoCoResource
second_title: Справочник по Aspose.PSD для .NET API
description: Класс SoCoResource. Этот ресурс содержит информацию о Color Fill Layers
type: docs
weight: 2980
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Класс SoCoResource. Этот ресурс содержит информацию о Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SoCoResource](socoresource)() | Инициализирует новый экземпляр[`SoCoResource`](../socoresource) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color) { get; set; } | Получает цвет RGB . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion) { get; } | Получает минимальную версию psd, необходимую для ресурса слоя. 0 означает отсутствие ограничений. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature) { get; } | Получает подпись ресурса слоя. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey) | Информационный ключ типа инструмента. |

### Примеры

В следующем примере показано, как редактировать SoCoResource (ресурс слоя для слоя заливки цветом).

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Нахождение FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Нахождение SoCoResource в списке ресурсов слоя
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Установка свойства SoCoResource Color
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [FillLayerResource](../filllayerresource)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
