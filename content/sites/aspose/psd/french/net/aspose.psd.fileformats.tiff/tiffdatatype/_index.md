---
title: TiffDataType
second_title: Référence de l'API Aspose.PSD pour .NET
description: Le type de données tiff.
type: docs
weight: 4140
url: /fr/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Le type de données tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne suffisent pas pour contenir les données de balise). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count) { get; } | Obtient le nombre d'éléments. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize) { get; } | Obtient la taille des données supplémentaires en octets (au cas où les 12 octets ne suffisent pas pour contenir les données de balise). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id) { get; } | Obtient la représentation entière de l'ID de balise. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid) { get; } | Obtient une valeur indiquant si les données de balise sont valides. La balise valide contient des données qui peuvent être conservées. La balise invalide ne peut pas être stockée. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid) { get; } | Obtient l'identifiant de la balise. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype) { get; } | Obtient le type de balise. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value) { get; set; } | Obtient ou définit la valeur que ce type de données contient. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag)(TiffStreamReader, long) | Lit les données de balise. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto)(object) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou apparaît à la même position dans l'ordre de tri que l'autre objet. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone)() | Effectue un clone profond de cette instance. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring)() | Renvoie unString qui représente cette instance. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata)(TiffStreamWriter) | Écrit les données de variable supplémentaires. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Écrit les données de variable. |

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
