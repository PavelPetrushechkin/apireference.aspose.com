---
title: General
second_title: Référence de l'API Aspose.GIS pour .NET
description: Convertit un nombre en une notation à virgule fixe ou scientifique plus compacte selon le type du nombre et si un spécificateur de précision est présent. Utilisation recommandée.
type: docs
weight: 30
url: /fr/net/aspose.gis/numericformat/general/
---
## NumericFormat.General method

Convertit un nombre en une notation à virgule fixe ou scientifique plus compacte, selon le type du nombre et si un spécificateur de précision est présent. Utilisation recommandée.

```csharp
public static NumericFormat General(int precision = 0)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| precision | Int32 | La précision définit le nombre maximum de chiffres significatifs pouvant apparaître dans la chaîne de résultat. Si la précision est nulle, la valeur "15" est utilisée. La précision maximale disponible est "17". |

### Return_Value

Le spécificateur de format général.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le nombre de chiffres significatifs est inférieur à 0 ou supérieur à 17. |

### Remarques

Le code interne génère des chaînes de nombres pour WKT via :ordinate.ToString("G", CultureInfo.InvariantCulture).

### Voir également

* class [NumericFormat](../../numericformat)
* espace de noms [Aspose.Gis](../../numericformat)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
