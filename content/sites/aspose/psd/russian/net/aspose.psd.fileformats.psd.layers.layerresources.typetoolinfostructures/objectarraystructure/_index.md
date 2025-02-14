---
title: ObjectArrayStructure
second_title: Справочник по Aspose.PSD для .NET API
description: Определяет класс ObjectArrayStructure который обычно содержитUnitArrayStructure./unitarraystructure array. Используется в файловых ресурсах PSD таких как PlLd Resource и SoLd Resource.
type: docs
weight: 3140
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
## ObjectArrayStructure class

Определяет класс ObjectArrayStructure, который обычно содержит[`UnitArrayStructure`](../unitarraystructure) array. Используется в файловых ресурсах PSD, таких как PlLd Resource и SoLd Resource.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure#constructor_1)(string, string, OSTypeStructure[]) | Инициализирует новый экземпляр[`ObjectArrayStructure`](../objectarraystructure) класс. |
| [ObjectArrayStructure](objectarraystructure#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | Инициализирует новый экземпляр[`ObjectArrayStructure`](../objectarraystructure) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid) { get; set; } | Получает или задает идентификатор класса массива объектов. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname) { get; set; } | Получает или задает имя класса массива объектов. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key) { get; } | Получает ключ структуры массива объектов. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | Получает или задает имя ключа. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length) { get; } | Получает[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) длина в байтах. |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount) { get; } | Получает количество подструктур массива объектов. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures) { get; set; } | Получает или задает копию массива структур. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | Получает длину заголовка. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |

## Поля

| Имя | Описание |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey) | Идентифицирует ключ структуры 'ObAr'. |

### Примеры

Следующий код демонстрирует поддержку подписей ObAr и UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### Смотрите также

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
