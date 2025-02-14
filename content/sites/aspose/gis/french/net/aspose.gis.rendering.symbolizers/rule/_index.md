---
title: Rule
second_title: Référence de l'API Aspose.GIS pour .NET
description: Une règle définie par lutilisateur pourRuleBasedSymbolizer./rulebasedsymbolizer .
type: docs
weight: 1820
url: /fr/net/aspose.gis.rendering.symbolizers/rule/
---
## Rule class

Une règle définie par l'utilisateur pour[`RuleBasedSymbolizer`](../rulebasedsymbolizer) .

```csharp
public class Rule
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Filter](../../aspose.gis.rendering.symbolizers/rule/filter) { get; } | Détermine si "filter-rule" doit appliquer le symbolisateur à l'entité. Si renvoie`true` symboliseur est utilisé ; sinon, la fonctionnalité est ignorée. |
| [IsElseRule](../../aspose.gis.rendering.symbolizers/rule/iselserule) { get; } | Obtient une valeur indiquant si cette règle est "else-rule". |
| [IsFilterRule](../../aspose.gis.rendering.symbolizers/rule/isfilterrule) { get; } | Obtient une valeur indiquant si cette règle est "filter-rule". |
| [Symbolizer](../../aspose.gis.rendering.symbolizers/rule/symbolizer) { get; } | Symboliseur à appliquer à l'entité. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [CreateElseRule](../../aspose.gis.rendering.symbolizers/rule/createelserule)(VectorSymbolizer) | Crée une nouvelle règle qui applique un symboliseur à l'entité chaque fois qu'elle ne correspond à aucune règle de filtre. |
| static [CreateFilterRule](../../aspose.gis.rendering.symbolizers/rule/createfilterrule)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | Crée une nouvelle règle qui applique un symboliseur à l'entité chaque fois qu'elle passe le filtre. |

### Voir également

* espace de noms [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers)
* Assemblée [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
