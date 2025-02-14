---
title: SpatialReferenceSystemType
second_title: Référence de l'API Aspose.GIS pour .NET
description: Représente le type de système de référence spatiale.
type: docs
weight: 2170
url: /fr/net/aspose.gis.spatialreferencing/spatialreferencesystemtype/
---
## SpatialReferenceSystemType enumeration

Représente le type de système de référence spatiale.

```csharp
public enum SpatialReferenceSystemType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Unknown | `0` | Valeur par défaut. Peut être renvoyé à partir de[`Type`](../spatialreferencesystem/type) s'il s'agit d'un SRS composé avec une combinaison invalide de SRS sous-jacents. Voir[`IsCompound`](../spatialreferencesystem/iscompound) . |
| Geographic | `1` | Le SRS géographique est basé sur la longitude angulaire et la latitude angulaire. Le SRS géographique peut être converti en[`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem) via[`AsGeographic`](../spatialreferencesystem/asgeographic) méthode. |
| Geocentric | `2` | Le SRS géocentrique est un SRS cartésien tridimensionnel dont l'origine est au centre de la Terre. Le SRS géocentrique peut être converti en[`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem) via[`AsGeocentric`](../spatialreferencesystem/asgeocentric) méthode. |
| Projected | `3` | Le SRS projeté est basé sur X linéaire et Y linéaire. Il est le résultat de l'application d'une projection sur unGeographic SRS. Le SRS projeté peut être converti en[`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem) via[`AsProjected`](../spatialreferencesystem/asprojected) méthode. |
| Vertical | `4` | Vertical SRS décrit la coordonnée de hauteur linéaire. Vertical SRS peut être converti en[`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem) via[`AsVertical`](../spatialreferencesystem/asvertical) méthode. |
| Local | `5` | Le SRS local relie les coordonnées à un objet, à d'autres la Terre. Le SRS local peut être converti en[`LocalSpatialReferenceSystem`](../localspatialreferencesystem) via[`AsLocal`](../spatialreferencesystem/aslocal) méthode. |

### Voir également

* espace de noms [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* Assemblée [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
