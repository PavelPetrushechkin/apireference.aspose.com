---
title: NewValueSpecifiedUnits
second_title: Référence de l'API Aspose.SVG pour .NET
description: Réinitialisez la valeur sous forme de nombre avec un type dunité associé remplaçant ainsi les valeurs de tous les attributs de lobjet.
type: docs
weight: 60
url: /fr/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Réinitialisez la valeur sous forme de nombre avec un type d'unité associé, remplaçant ainsi les valeurs de tous les attributs de l'objet.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| unitType | UInt16 | Le type d'unité pour la valeur. |
| valueInSpecifiedUnits | Single | La nouvelle valeur.. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err) Levé si unitType est SVG_LENGTHTYPE_UNKNOWN ou n'est pas une constante de type d'unité valide (l'une des autres constantes SVG_LENGTHTYPE_* définies sur cette interface). |
| [DOMException](../../../aspose.svg.dom/domexception) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err) Levé lorsque la longueur correspond à un attribut en lecture seule ou lorsque l'objet lui-même est en lecture seule. |

### Voir également

* class [SVGLength](../../svglength)
* espace de noms [Aspose.Svg.DataTypes](../../svglength)
* Assemblée [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
