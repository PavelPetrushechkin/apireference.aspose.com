---
title: SetValues
second_title: Référence de l'API Aspose.GIS pour .NET
description: Définit de nouvelles valeurs pour tous les attributs. Envisagez également dutiliserCopyValuesaspose.gis/feature/copyvalues méthode pour rationaliser les valeurs de réglage en un seul appel.
type: docs
weight: 120
url: /fr/net/aspose.gis/feature/setvalues/
---
## Feature.SetValues method

Définit de nouvelles valeurs pour tous les attributs. Envisagez également d'utiliser[`CopyValues`](../copyvalues) méthode pour rationaliser les valeurs de réglage en un seul appel.

```csharp
public int SetValues(object[] values)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| values | Object[] | Le tableau des nouvelles valeurs. |

### Return_Value

Le nombre de valeurs d'attribut définies.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'argumentation ne peut être`null`. |
| ArgumentException | L'attribut portant ce nom n'existe pas dans cette couche. |
| InvalidOperationException | L'attribut n'est pas verrouillé. |
| InvalidCastException | Le type de la valeur n'implémente pasIConvertible. |
| FormatException | La conversion a échoué car la valeur est dans un format incorrect. |
| OverflowException | La conversion a échoué en raison d'un débordement. |

### Remarques

Cette méthode convertit automatiquement chaque valeur en type d'attribut.  La longueur du tableau de valeurs n'a pas besoin de correspondre au nombre d'attributs dans l'entité. Si la longueur du tableau est supérieure au nombre d'attributs, toutes les valeurs du tableau sont copiées dans les attributs ; si elle est inférieure, seul le nombre de valeurs de la longueur du tableau est copié dans les attributs, en commençant par la valeur de l'attribut avec l'ordinal 0.

### Voir également

* class [Feature](../../feature)
* espace de noms [Aspose.Gis](../../feature)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
