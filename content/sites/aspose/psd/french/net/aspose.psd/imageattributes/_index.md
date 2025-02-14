---
title: ImageAttributes
second_title: Référence de l'API Aspose.PSD pour .NET
description: UnImageAttributes./imageattributes Lobjet contient des informations sur la manière dont les couleurs des bitmaps et des métafichiers sont manipulées lors du rendu. UnImageAttributes./imageattributes Lobjet conserve plusieurs paramètres dajustement des couleurs notamment les matrices dajustement des couleurs les matrices dajustement des niveaux de gris les valeurs de correction gamma les tables de cartes de couleurs et les valeurs de seuil de couleur. Pendant le rendu les couleurs peuvent être corrigées assombries éclaircies et supprimées. Pour appliquer de telles manipulations initialisez unImageAttributes./imageattributesobjet et passez le chemin de celuiciImageAttributes./imageattributes objet ainsi que le chemin dunImage./image  à la méthode DrawImage.
type: docs
weight: 4540
url: /fr/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Un[`ImageAttributes`](../imageattributes) L'objet contient des informations sur la manière dont les couleurs des bitmaps et des métafichiers sont manipulées lors du rendu. Un[`ImageAttributes`](../imageattributes) L'objet conserve plusieurs paramètres d'ajustement des couleurs, notamment les matrices d'ajustement des couleurs, les matrices d'ajustement des niveaux de gris, les valeurs de correction gamma, les tables de cartes de couleurs et les valeurs de seuil de couleur. Pendant le rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un[`ImageAttributes`](../imageattributes)objet et passez le chemin de celui-ci[`ImageAttributes`](../imageattributes) objet (ainsi que le chemin d'un[`Image`](../image) ) à la méthode DrawImage.

```csharp
public sealed class ImageAttributes
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageAttributes](imageattributes)() | Default_Constructor |

## Méthodes

| Nom | La description |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable)() | Efface la table de remappage des couleurs du pinceau de ce[`ImageAttributes`](../imageattributes) objet. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey#clearcolorkey)() | Efface la clé de couleur (plage de transparence) pour la catégorie par défaut. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix#clearcolormatrix)() | Efface la matrice de réglage des couleurs pour la catégorie par défaut. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Efface la matrice de réglage des couleurs pour une catégorie spécifiée. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma#cleargamma)() | Désactive la correction gamma pour la catégorie par défaut. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Désactive la correction gamma pour une catégorie spécifiée. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop#clearnoop)() | Efface le paramètre NoOp pour la catégorie par défaut. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Efface le paramètre NoOp pour une catégorie spécifiée. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel#clearoutputchannel)() | Efface le paramètre du canal de sortie CMJN (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Efface le paramètre de canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Efface le paramètre de profil de couleur du canal de sortie pour la catégorie par défaut. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Efface le paramètre de profil de couleur du canal de sortie pour une catégorie spécifiée. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable#clearremaptable)() | Efface la table de remappage des couleurs pour la catégorie par défaut. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Efface la table de remappage des couleurs pour une catégorie spécifiée. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold#clearthreshold)() | Efface la valeur de seuil pour la catégorie par défaut. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Efface la valeur de seuil pour une catégorie spécifiée. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable)(ColorMap[]) | Définit la table de remappage des couleurs pour la catégorie de pinceaux. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Définit la clé de couleur pour la catégorie par défaut. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour la catégorie par défaut. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour la catégorie par défaut. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Définit la matrice de réglage des couleurs et la matrice de réglage des niveaux de gris pour une catégorie spécifiée. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Définit la matrice de réglage des couleurs pour la catégorie par défaut. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Définit la matrice de réglage des couleurs pour la catégorie par défaut. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Définit la matrice de réglage des couleurs pour une catégorie spécifiée. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma#setgamma)(float) | Définit la valeur gamma pour la catégorie par défaut. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Définit la valeur gamma pour une catégorie spécifiée. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop#setnoop)() | Désactive le réglage des couleurs pour la catégorie par défaut. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Désactive le réglage des couleurs pour une catégorie spécifiée. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Définit le canal de sortie CMJN (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Définit le canal de sortie CMJN (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Définit le fichier de profil de couleur du canal de sortie pour la catégorie par défaut. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Définit le fichier de profil de couleur du canal de sortie pour une catégorie spécifiée. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Définit la table de remappage des couleurs pour la catégorie par défaut. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Définit la table de remappage des couleurs pour une catégorie spécifiée. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold#setthreshold)(float) | Définit le seuil (plage de transparence) pour la catégorie par défaut. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Définit le seuil (plage de transparence) pour une catégorie spécifiée. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Définit le mode d'habillage qui est utilisé pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Définit le mode d'habillage et la couleur utilisés pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Définit le mode d'habillage et la couleur utilisés pour décider comment juxtaposer une texture sur une forme ou aux limites de la forme. Une texture est disposée en mosaïque sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
