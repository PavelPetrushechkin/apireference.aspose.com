---
title: DecryptionPassword
second_title: Referencia de la API de Aspose.ZIP para .NET
description: Obtiene o establece la contraseña para descifrar las entradas y los nombres de las entradas.
type: docs
weight: 20
url: /es/net/aspose.zip.rar/rararchiveloadoptions/decryptionpassword/
---
## RarArchiveLoadOptions.DecryptionPassword property

Obtiene o establece la contraseña para descifrar las entradas y los nombres de las entradas.

```csharp
public string DecryptionPassword { get; set; }
```

### Ejemplos

Puede proporcionar la contraseña de descifrado una vez en la extracción del archivo.

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

### Ver también

* method [Open](../../rararchiveentry/open)
* class [RarArchiveLoadOptions](../../rararchiveloadoptions)
* espacio de nombres [Aspose.Zip.Rar](../../rararchiveloadoptions)
* asamblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
