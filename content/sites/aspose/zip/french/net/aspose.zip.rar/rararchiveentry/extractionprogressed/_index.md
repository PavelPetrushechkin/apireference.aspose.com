---
title: ExtractionProgressed
second_title: Référence de l'API Aspose.ZIP pour .NET
description: Se déclenche lorsquune partie du flux brut est extraite.
type: docs
weight: 80
url: /fr/net/aspose.zip.rar/rararchiveentry/extractionprogressed/
---
## RarArchiveEntry.ExtractionProgressed event

Se déclenche lorsqu'une partie du flux brut est extraite.

```csharp
public event EventHandler<ProgressEventArgs> ExtractionProgressed;
```

### Remarques

L'expéditeur de l'événement est un[`RarArchiveEntry`](../../rararchiveentry) exemple.

### Exemples

```csharp
archive.Entries[0].ExtractionProgressed += (s, e) => {  int percent = (int)((100 * e.ProceededBytes) / ((RarArchiveEntry)s).UncompressedSize); };
```

### Voir également

* class [ProgressEventArgs](../../../aspose.zip/progresseventargs)
* class [RarArchiveEntry](../../rararchiveentry)
* espace de noms [Aspose.Zip.Rar](../../rararchiveentry)
* Assemblée [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
