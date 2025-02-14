---
title: PageDeviceColorSpaceUsage.PageDeviceColorSpaceUsageOption
second_title: Справочник по Aspose.Page для .NET API
description: ОписываетPageDeviceColorSpaceUsage./pagedevicecolorspaceusage параметры функции.
type: docs
weight: 1880
url: /ru/net/aspose.page.xps.xpsmetadata/pagedevicecolorspaceusage.pagedevicecolorspaceusageoption/
---
## PageDeviceColorSpaceUsage.PageDeviceColorSpaceUsageOption class

Описывает[`PageDeviceColorSpaceUsage`](../pagedevicecolorspaceusage) параметры функции.

```csharp
public sealed class PageDeviceColorSpaceUsageOption : Option
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Получает имя элемента. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/option/add)(params IOptionItem[]) | Добавляет список элементов в конец списка элементов этой опции. Каждый должен быть[`ScoredProperty`](../scoredproperty) или же[`Property`](../property) экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| static [MatchToDefault](../../aspose.page.xps.xpsmetadata/pagedevicecolorspaceusageoption/matchtodefault) | Если устройство определяет, что профиль, указанный[`PageDeviceColorSpaceProfileURI`](../pagedevicecolorspaceprofileuri) параметр можно использовать в качестве профиля цветового пространства устройства, все элементы, использующие один и тот же профиль, рассматриваются как уже заданные в цветовом пространстве устройства. Все остальные элементы ДОЛЖНЫ использовать профиль, указанный для этого элемента. Если профиль нельзя использовать в качестве профиля цветового пространства устройства, элементы, использующие этот профиль, ДОЛЖНЫ управлять цветом, как и любой другой элемент, использующий цветовой профиль. |
| static [OverrideDeviceDefault](../../aspose.page.xps.xpsmetadata/pagedevicecolorspaceusageoption/overridedevicedefault) | Если профиль, заданный параметром PageDeviceColorSpaceProfileURI, имеет количество каналов, соответствующее количеству основных цветов устройства, его СЛЕДУЕТ использовать вместо внутреннего управления цветом устройства для всех элементов. Предполагается, что элементы, использующие этот профиль, имеют цвет устройства. пространство и больше не будет управляться цветом. |

### Смотрите также

* class [Option](../option)
* class [PageDeviceColorSpaceUsage](../pagedevicecolorspaceusage)
* пространство имен [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* сборка [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
