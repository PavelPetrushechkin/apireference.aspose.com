---
title: Add
second_title: Référence de l'API Aspose.GIS pour .NET
description: Ajoute de nouveauxLabelingRuleaspose.gis.rendering.labelings/labelingrule .
type: docs
weight: 40
url: /fr/net/aspose.gis.rendering.labelings/rulebasedlabeling/add/
---
## Add(Func&lt;Feature, bool&gt;, Labeling) {#add_1}

Ajoute de nouveaux[`LabelingRule`](../../labelingrule) .

```csharp
public void Add(Func<Feature, bool> filter, Labeling labeling)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filter | Func`2 | Détermine quand l'étiquetage doit être appliqué à une entité. |
| labeling | Labeling | Libellé à appliquer à une entité lorsque*filter* renvoie vrai. |

### Voir également

* class [Feature](../../../aspose.gis/feature)
* class [Labeling](../../labeling)
* class [RuleBasedLabeling](../../rulebasedlabeling)
* espace de noms [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling)
* Assemblée [Aspose.GIS](../../../)

---

## Add(LabelingRule) {#add}

Ajoute une règle.

```csharp
public void Add(LabelingRule rule)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rule | LabelingRule | Règle à ajouter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'argument est`null`. |

### Voir également

* class [LabelingRule](../../labelingrule)
* class [RuleBasedLabeling](../../rulebasedlabeling)
* espace de noms [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
