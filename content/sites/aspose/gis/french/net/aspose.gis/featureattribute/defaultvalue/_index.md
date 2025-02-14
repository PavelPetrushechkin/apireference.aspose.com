---
title: DefaultValue
second_title: Référence de l'API Aspose.GIS pour .NET
description: Obtient ou définit une valeur pour lattribut qui indique des données manquantes.
type: docs
weight: 50
url: /fr/net/aspose.gis/featureattribute/defaultvalue/
---
## FeatureAttribute.DefaultValue property

Obtient ou définit une valeur pour l'attribut, qui indique des données manquantes.

```csharp
public object DefaultValue { get; set; }
```

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | L'attribut est verrouillé. |
| InvalidOperationException | L'attribut ne permet pas`nul` valeurs. |

### Remarques

C'est la valeur représentant une information manquante, lorsqu'un attribut ne permet pas`nul` value. Pour les attributs qui autorisent`nul` valeurs ([`CanBeNull`](../canbenull) ==`vrai` ),`DefaultValue` est`nul` sauf modification explicite.

### Voir également

* class [FeatureAttribute](../../featureattribute)
* espace de noms [Aspose.Gis](../../featureattribute)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
