---
title: FeaturesBasedConfiguration
second_title: Справочник по Aspose.GIS for .NET API
description: Обратный вызов который используется для настройки этого символизатора перед визуализацией центра кластера.
type: docs
weight: 20
url: /ru/net/aspose.gis.rendering.symbolizers/markercluster/featuresbasedconfiguration/
---
## MarkerCluster.FeaturesBasedConfiguration property

Обратный вызов, который используется для настройки этого символизатора перед визуализацией центра кластера.

```csharp
public Action<IEnumerable<Feature>, MarkerCluster> FeaturesBasedConfiguration { get; set; }
```

### Примечания

Этот обратный вызов вызывается перед рендерингом каждого центра кластера. Он принимает объекты, которые должны быть визуализированы, и клон этого символизатора. Изменяя свойства клона, можно обновить поведение символизатора на основе атрибутов функций.

### Смотрите также

* class [Feature](../../../aspose.gis/feature)
* class [MarkerCluster](../../markercluster)
* пространство имен [Aspose.Gis.Rendering.Symbolizers](../../markercluster)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
