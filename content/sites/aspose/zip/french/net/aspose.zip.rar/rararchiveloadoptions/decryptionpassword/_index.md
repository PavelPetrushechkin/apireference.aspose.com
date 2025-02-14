---
title: DecryptionPassword
second_title: Référence de l'API Aspose.ZIP pour .NET
description: Obtient ou définit le mot de passe pour déchiffrer les entrées et les noms dentrée.
type: docs
weight: 20
url: /fr/net/aspose.zip.rar/rararchiveloadoptions/decryptionpassword/
---
## RarArchiveLoadOptions.DecryptionPassword property

Obtient ou définit le mot de passe pour déchiffrer les entrées et les noms d'entrée.

```csharp
public string DecryptionPassword { get; set; }
```

### Exemples

Vous pouvez fournir un mot de passe de déchiffrement une fois lors de l'extraction de l'archive.

```csharp
using (FileStream fs = File.OpenRead("encrypted_archive.rar"))
{
    using (var extracted = File.Create("extracted.bin"))
    {
        using (RarArchive archive = new RarArchive(fs, new ArchiveLoadOptions() { DecryptionPassword = "p@s$" }))
        {
            using (var decompressed = archive.Entries[0].Open())
            {
                byte[] b = new byte[8192];
                int bytesRead;
                while (0 < (bytesRead = decompressed.Read(b, 0, b.Length)))
                    extracted.Write(b, 0, bytesRead);
                
            }
        }
    }
}
```

### Voir également

* method [Open](../../rararchiveentry/open)
* class [RarArchiveLoadOptions](../../rararchiveloadoptions)
* espace de noms [Aspose.Zip.Rar](../../rararchiveloadoptions)
* Assemblée [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
