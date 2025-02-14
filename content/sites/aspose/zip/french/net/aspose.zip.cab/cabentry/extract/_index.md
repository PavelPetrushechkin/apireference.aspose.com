---
title: Extract
second_title: Référence de l'API Aspose.ZIP pour .NET
description: Extrait lentrée du système de fichiers par le chemin fourni.
type: docs
weight: 30
url: /fr/net/aspose.zip.cab/cabentry/extract/
---
## Extract(string) {#extract}

Extrait l'entrée du système de fichiers par le chemin fourni.

```csharp
public FileSystemInfo Extract(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès au fichier de destination. Si le fichier existe déjà, il sera écrasé. |

### Return_Value

Les informations de fichier du fichier composé.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *path* est nul. |
| SecurityException | L'appelant n'a pas l'autorisation requise pour accéder. |
| ArgumentException | La*path* est vide, ne contient que des espaces blancs ou contient des caractères non valides. |
| UnauthorizedAccessException | Accéder au dossier*path* est refusé. |
| PathTooLongException | Le spécifié*path*, nom de fichier ou les deux dépassent la longueur maximale définie par le système. Par exemple, sur les plates-formes Windows, les chemins doivent comporter moins de 248 caractères et les noms de fichiers doivent comporter moins de 260 caractères. |
| NotSupportedException | Fichier à*path* contient deux-points (:) au milieu de la chaîne. |

### Exemples

```csharp
using (var archive = new CabArchive("archive.cab"))
{
    archive.Entries[0].Extract("data.bin");
}
```

### Voir également

* class [CabEntry](../../cabentry)
* espace de noms [Aspose.Zip.Cab](../../cabentry)
* Assemblée [Aspose.Zip](../../../)

---

## Extract(Stream) {#extract_1}

Extrait l'entrée du flux fourni.

```csharp
public void Extract(Stream destination)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| destination | Stream | Flux de destination. Doit être inscriptible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *destination* ne prend pas en charge l'écriture. |

### Exemples

Extraire une entrée de l'archive cab.

```csharp
using (var archive = new CabArchive("archive.cab"))
{
    archive.Entries[0].Extract(httpResponseStream);
}
```

### Voir également

* class [CabEntry](../../cabentry)
* espace de noms [Aspose.Zip.Cab](../../cabentry)
* Assemblée [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
