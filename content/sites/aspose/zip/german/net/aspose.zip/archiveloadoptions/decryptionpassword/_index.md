---
title: DecryptionPassword
second_title: Aspose.ZIP für .NET-API-Referenz
description: Ruft das Passwort zum Entschlüsseln von Einträgen ab oder setzt es.
type: docs
weight: 20
url: /de/net/aspose.zip/archiveloadoptions/decryptionpassword/
---
## ArchiveLoadOptions.DecryptionPassword property

Ruft das Passwort zum Entschlüsseln von Einträgen ab oder setzt es.

```csharp
public string DecryptionPassword { get; set; }
```

### Beispiele

Sie können das Entschlüsselungskennwort einmal beim Extrahieren des Archivs angeben.

```csharp
using (FileStream fs = File.OpenRead("encrypted_archive.zip"))
{
    using (var extracted = File.Create("extracted.bin"))
    {
        using (Archive archive = new Archive(fs, new ArchiveLoadOptions() { DecryptionPassword = "p@s$" }))
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

### Siehe auch

* method [Open](../../archiveentry/open)
* class [ArchiveLoadOptions](../../archiveloadoptions)
* namensraum [Aspose.Zip](../../archiveloadoptions)
* Montage [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
