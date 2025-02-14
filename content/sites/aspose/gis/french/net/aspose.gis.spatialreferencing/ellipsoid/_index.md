---
title: Ellipsoid
second_title: Référence de l'API Aspose.GIS pour .NET
description: Ellipsoïde représente un ellipsoïde qui se rapproche de la terre.
type: docs
weight: 1970
url: /fr/net/aspose.gis.spatialreferencing/ellipsoid/
---
## Ellipsoid class

Ellipsoïde représente un ellipsoïde, qui se rapproche de la terre.

```csharp
public class Ellipsoid : IdentifiableObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Ellipsoid](ellipsoid)(string, double, double, Identifier) | Crée un nouvel ellipsoïde. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Airy](../../aspose.gis.spatialreferencing/ellipsoid/airy) { get; } | Ellipsoïde aérien. |
| static [Grs80](../../aspose.gis.spatialreferencing/ellipsoid/grs80) { get; } | GRS 1980 Ellipsoïde. |
| static [Wgs72](../../aspose.gis.spatialreferencing/ellipsoid/wgs72) { get; } | Ellipsoïde WGS 72. |
| static [Wgs84](../../aspose.gis.spatialreferencing/ellipsoid/wgs84) { get; } | Ellipsoïde WGS 84. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode) { get; } | Si cet identifiant d'objet est un identifiant EPSG - retourne son code. Sinon - renvoie -1. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier) { get; } | Identifiant de cet objet identifiable. |
| [InverseFlattening](../../aspose.gis.spatialreferencing/ellipsoid/inverseflattening) { get; } | Aplatissement inverse de l'ellipsoïde. 0 s'il s'agit d'une sphère. |
| [IsSphere](../../aspose.gis.spatialreferencing/ellipsoid/issphere) { get; } | Détecte si cet ellipsoïde est une sphère. |
| [IsValid](../../aspose.gis.spatialreferencing/ellipsoid/isvalid) { get; } | Détecte si l'ellipsoïde est valide : son demi-grand axe est supérieur à 0 et l'aplatissement inverse est positif ou égal à 0. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name) { get; } | Nom de cet objet. |
| [SemiMajorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semimajoraxis) { get; } | Demi grand axe de l'ellipsoïde. |
| [SemiMinorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semiminoraxis) { get; } | Demi petit axe de l'ellipsoïde. Égal au demi-grand axe s'il s'agit d'une sphère. |

## Méthodes

| Nom | La description |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent)(Ellipsoid) | Détermine si deux ellipsoïdes sont équivalents. Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même demi-grand axe et un aplatissement inverse. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring)() | Retourne une chaîne qui représente l'objet actuel. |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent)(Ellipsoid, Ellipsoid) | Détermine si deux ellipsoïdes sont équivalents. Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même demi-grand axe et un aplatissement inverse. |

### Voir également

* class [IdentifiableObject](../identifiableobject)
* espace de noms [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* Assemblée [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
