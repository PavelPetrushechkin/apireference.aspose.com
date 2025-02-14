---
title: VectorMapLayer
second_title: Справочник по Aspose.GIS for .NET API
description: Слой внутриMap./map который представляет данные векторного слоя.
type: docs
weight: 1900
url: /ru/net/aspose.gis.rendering/vectormaplayer/
---
## VectorMapLayer class

Слой внутри[`Map`](../map) который представляет данные векторного слоя.

```csharp
public class VectorMapLayer : MapLayer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorMapLayer](vectormaplayer#constructor)(FeaturesSequence) | Создает новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer](vectormaplayer#constructor_1)(FeaturesSequence, VectorSymbolizer) | Создает новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer](vectormaplayer#constructor_5)(VectorLayer, bool) | Создает новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer](vectormaplayer#constructor_2)(FeaturesSequence, VectorSymbolizer, Labeling) | Создает новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer](vectormaplayer#constructor_4)(VectorLayer, VectorSymbolizer, bool) | Создает новый экземпляр. |
| [VectorMapLayer](vectormaplayer#constructor_3)(VectorLayer, VectorSymbolizer, Labeling, bool) | Создает новый экземпляр. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [FeaturesSequence](../../aspose.gis.rendering/vectormaplayer/featuressequence) { get; } | Последовательность функций, представленная этим`ВекторКартаСлой` . |
| [Labeling](../../aspose.gis.rendering/vectormaplayer/labeling) { get; set; } | Задает параметры деформации слоя карты. |
| [Opacity](../../aspose.gis.rendering/maplayer/opacity) { get; set; } | Непрозрачность слоя. |
| [Symbolizer](../../aspose.gis.rendering/vectormaplayer/symbolizer) { get; set; } | Символизатор, используемый для визуализации объектов слоя. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../aspose.gis.rendering/vectormaplayer/dispose)() | Удаляет ресурсы. |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld#importsld)(AbstractPath, SldImportOptions) | Импортирует стиль из файла описателя стилизованного слоя, расположенного по указанному пути. |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld#importsld_1)(string, SldImportOptions) | Импортирует стиль из файла описателя стилизованного слоя, расположенного по указанному пути. |
| [ImportSldFromString](../../aspose.gis.rendering/vectormaplayer/importsldfromstring)(string, SldImportOptions) | Импортирует стиль из указанной строки описателя стилизованного слоя. |

### Смотрите также

* class [MapLayer](../maplayer)
* пространство имен [Aspose.Gis.Rendering](../../aspose.gis.rendering)
* сборка [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
