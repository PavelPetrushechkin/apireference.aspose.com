---
title: IStyleSheet
second_title: Référence de l'API Aspose.SVG pour .NET
description: Linterface StyleSheet est linterface de base abstraite pour tout type de feuille de style. Il représente une seule feuille de style associée à un document structuré.
type: docs
weight: 740
url: /fr/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

L'interface StyleSheet est l'interface de base abstraite pour tout type de feuille de style. Il représente une seule feuille de style associée à un document structuré.

```csharp
public interface IStyleSheet
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled) { get; set; } | false si la feuille de style est appliquée au document. vrai si ce n'est pas le cas. La modification de cet attribut peut entraîner une nouvelle résolution de style pour le document. Une feuille de style s'applique uniquement si une définition de support appropriée est présente et si l'attribut disabled est faux. Ainsi, si le média ne s'applique pas à l'agent utilisateur actuel, l'attribut désactivé est ignoré. |
| [Href](../../aspose.svg.dom.css/istylesheet/href) { get; } | Si la feuille de style est une feuille de style liée, la valeur de son attribut est son emplacement. Pour les feuilles de style en ligne, la valeur de cet attribut est nulle. |
| [Media](../../aspose.svg.dom.css/istylesheet/media) { get; } | Le support de destination prévu pour les informations de style. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode) { get; } | Le nœud qui associe cette feuille de style au document. Pour HTML, il peut s'agir de l'élément LINK ou STYLE correspondant. Pour XML, il peut s'agir de l'instruction de traitement de liaison. Pour les feuilles de style incluses dans d'autres feuilles de style, la valeur de cet attribut est null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet) { get; } | Pour les langages de feuille de style qui prennent en charge le concept d'inclusion de feuille de style, cet attribut représente la feuille de style incluse, si elle existe. Si la feuille de style est une feuille de style de niveau supérieur ou si le langage de la feuille de style ne prend pas en charge l'inclusion, la valeur de cet attribut est null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title) { get; } | Le titre de l'avis. |
| [Type](../../aspose.svg.dom.css/istylesheet/type) { get; } | Ceci spécifie le langage de feuille de style pour cette feuille de style. Le langage de la feuille de style est spécifié en tant que type de contenu (par exemple "text/css"). |

### Voir également

* espace de noms [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* Assemblée [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
