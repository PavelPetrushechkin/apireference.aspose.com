---
title: DisplayName
second_title: Справочник по Aspose.PSD для .NET API
description: Получает или задает отображаемое имя слоя.
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Получает или задает отображаемое имя слоя.

```csharp
public string DisplayName { get; set; }
```

### Стоимость имущества

Отображаемое имя слоя.

### Примеры

В следующем примере демонстрируется возможность установки значения DisplayName, при котором имя слоя отображается правильно.

```csharp
[C#]

// вносим изменения в имена слоев и сохраняем их
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // устанавливаем новое значение в свойство DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Смотрите также

* class [Layer](../../layer)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
