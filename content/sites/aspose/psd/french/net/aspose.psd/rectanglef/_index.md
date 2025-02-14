---
title: RectangleF
second_title: Référence de l'API Aspose.PSD pour .NET
description: Stocke un ensemble de quatre nombres à virgule flottante qui représentent lemplacement et la taille dun rectangle.
type: docs
weight: 5280
url: /fr/net/aspose.psd/rectanglef/
---
## RectangleF structure

Stocke un ensemble de quatre nombres à virgule flottante qui représentent l'emplacement et la taille d'un rectangle.

```csharp
public struct RectangleF
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Initialise une nouvelle instance du[`RectangleF`](../rectanglef) structure avec l'emplacement et la taille spécifiés. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Initialise une nouvelle instance du[`RectangleF`](../rectanglef) structure avec l'emplacement et la taille spécifiés. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty) { get; } | Obtient une nouvelle instance du[`RectangleF`](../rectanglef) structure qui a[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) et[`Height`](./height) valeurs mises à zéro. |
| [Bottom](../../aspose.psd/rectanglef/bottom) { get; set; } | Obtient ou définit la coordonnée y qui est la somme de[`Y`](./y) et[`Height`](./height) de cela[`RectangleF`](../rectanglef)structure. |
| [Height](../../aspose.psd/rectanglef/height) { get; set; } | Obtient ou définit la hauteur de ce[`RectangleF`](../rectanglef)structure. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty) { get; } | Obtient une valeur indiquant si le[`Width`](./width) ou[`Height`](./height) propriété de ce[`RectangleF`](../rectanglef) a une valeur de zéro. |
| [Left](../../aspose.psd/rectanglef/left) { get; set; } | Obtient ou définit la coordonnée x du bord gauche de ce[`RectangleF`](../rectanglef)structure. |
| [Location](../../aspose.psd/rectanglef/location) { get; set; } | Obtient ou définit les coordonnées du coin supérieur gauche de cette[`RectangleF`](../rectanglef)structure. |
| [Right](../../aspose.psd/rectanglef/right) { get; set; } | Obtient ou définit la coordonnée x qui est la somme de[`X`](./x) et[`Width`](./width) de cela[`RectangleF`](../rectanglef)structure. |
| [Size](../../aspose.psd/rectanglef/size) { get; set; } | Obtient ou définit la taille de ce[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.psd/rectanglef/top) { get; set; } | Obtient ou définit la coordonnée y du bord supérieur de ce[`RectangleF`](../rectanglef)structure. |
| [Width](../../aspose.psd/rectanglef/width) { get; set; } | Obtient ou définit la largeur de cette[`RectangleF`](../rectanglef)structure. |
| [X](../../aspose.psd/rectanglef/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de cette[`RectangleF`](../rectanglef)structure. |
| [Y](../../aspose.psd/rectanglef/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de ce[`RectangleF`](../rectanglef)structure. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Crée un[`RectangleF`](../rectanglef) structure avec coin supérieur gauche et coin inférieur droit aux emplacements spécifiés. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints)(PointF, PointF) | Crée un nouveau[`Rectangle`](../rectangle) à partir de deux points spécifiés. Deux verticules du créé[`Rectangle`](../rectangle) sera égal au passé*point1* et*point2* . Il s'agirait généralement des sommets opposés. |
| static [Inflate](../../aspose.psd/rectanglef/inflate)(RectangleF, float, float) | Crée et renvoie une copie gonflée du spécifié[`RectangleF`](../rectanglef) structure. La copie est gonflée du montant spécifié. Le rectangle d'origine reste inchangé. |
| static [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF, RectangleF) | Renvoie un[`RectangleF`](../rectanglef) structure qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection et vide[`RectangleF`](../rectanglef) est renvoyé. |
| static [Union](../../aspose.psd/rectanglef/union)(RectangleF, RectangleF) | Crée le plus petit troisième rectangle possible pouvant contenir les deux rectangles formant une union. |
| [Contains](../../aspose.psd/rectanglef/contains#contains)(PointF) | Détermine si le point spécifié est contenu dans ce[`RectangleF`](../rectanglef)structure. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_1)(RectangleF) | Détermine si la région rectangulaire représentée par*rect* est entièrement contenu dans ce[`RectangleF`](../rectanglef)structure. |
| [Contains](../../aspose.psd/rectanglef/contains#contains_2)(float, float) | Détermine si le point spécifié est contenu dans ce[`RectangleF`](../rectanglef)structure. |
| override [Equals](../../aspose.psd/rectanglef/equals)(object) | Teste si*obj* est un[`RectangleF`](../rectanglef) avec le même emplacement et la même taille que celui-ci[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode)() | Obtient le code de hachage pour cela[`RectangleF`](../rectanglef)structure. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate)(SizeF) | Gonfle ça[`RectangleF`](../rectanglef) par le montant spécifié. |
| [Inflate](../../aspose.psd/rectanglef/inflate#inflate_1)(float, float) | Gonfle ça[`RectangleF`](../rectanglef) structure par le montant spécifié. |
| [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF) | Remplace ceci[`RectangleF`](../rectanglef) structure avec l'intersection d'elle-même et du spécifié[`RectangleF`](../rectanglef)structure. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith)(RectangleF) | Détermine si ce rectangle coupe avec*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize)() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, gauche moins que droite et haut moins que bas. |
| [Offset](../../aspose.psd/rectanglef/offset#offset)(PointF) | Ajuste l'emplacement de ce rectangle du montant spécifié. |
| [Offset](../../aspose.psd/rectanglef/offset#offset_1)(float, float) | Ajuste l'emplacement de ce rectangle du montant spécifié. |
| override [ToString](../../aspose.psd/rectanglef/tostring)() | Convertit les attributs de ce[`RectangleF`](../rectanglef) en une chaîne lisible par l'homme. |
| [operator /](../../aspose.psd/rectanglef/op_division) | Implémente l'opérateur /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality) | Teste si deux[`RectangleF`](../rectanglef) les structures ont un emplacement et une taille égaux. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit) | Convertit le spécifié[`Rectangle`](../rectangle) structurer à un[`RectangleF`](../rectanglef)structure. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality) | Teste si deux[`RectangleF`](../rectanglef) les structures diffèrent par leur emplacement ou leur taille. |
| [operator *](../../aspose.psd/rectanglef/op_multiply) | Implémente l'opérateur *. |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
