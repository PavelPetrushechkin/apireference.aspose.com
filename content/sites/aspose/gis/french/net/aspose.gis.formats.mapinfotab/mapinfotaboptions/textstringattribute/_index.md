---
title: TextStringAttribute
second_title: Référence de l'API Aspose.GIS pour .NET
description: Spécifie le nom de lattribut qui représente le texte de lobjet graphique Text.
type: docs
weight: 30
url: /fr/net/aspose.gis.formats.mapinfotab/mapinfotaboptions/textstringattribute/
---
## MapInfoTabOptions.TextStringAttribute property

Spécifie le nom de l'attribut qui représente le texte de l'objet graphique 'Text'.

```csharp
public string TextStringAttribute { get; set; }
```

### Remarques

MapInfo Tab Format spécifie un objet graphique de type 'Text'. L'objet graphique 'Text' représente une étiquette sur une carte. Nous exportons les objets graphiques 'Text' as a[`Feature`](../../../aspose.gis/feature) avec[`Polygon`](../../../aspose.gis.geometries/polygon) géométrie qui délimite l'étiquette. Le texte de l'étiquette est exporté en tant que[`FeatureAttribute`](../../../aspose.gis/featureattribute) . Cette propriété spécifie le nom de l'attribut utilisé pour exporter le texte de l'étiquette. La valeur par défaut est`"chaîne de texte"` .

### Voir également

* class [MapInfoTabOptions](../../mapinfotaboptions)
* espace de noms [Aspose.Gis.Formats.MapInfoTab](../../mapinfotaboptions)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
