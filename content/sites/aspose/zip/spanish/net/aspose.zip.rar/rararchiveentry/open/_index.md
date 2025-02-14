---
title: Open
second_title: Referencia de la API de Aspose.ZIP para .NET
description: Abre la entrada para su extracción y proporciona un flujo con contenido de entrada descomprimido.
type: docs
weight: 100
url: /es/net/aspose.zip.rar/rararchiveentry/open/
---
## RarArchiveEntry.Open method

Abre la entrada para su extracción y proporciona un flujo con contenido de entrada descomprimido.

```csharp
public Stream Open(string password = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| password | String | Contraseña opcional para el descifrado. También se puede configurar dentro[`DecryptionPassword`](../../rararchiveloadoptions/decryptionpassword). |

### Valor_devuelto

La secuencia que representa el contenido de la entrada.

### Observaciones

Lea de la transmisión para obtener el contenido original del archivo. Ver sección de ejemplos.

### Ejemplos

Uso:

.NET 4.0 y superior: utilice el método Stream.CopyTo:

```csharp
decompressed.CopyTo(httpResponse.OutputStream)
```

.NET 3.5 y anterior - copiar bytes manualmente:

```csharp
byte[] buffer = new byte[8192];
int bytesRead;
while (0 < (bytesRead = decompressed.Read(buffer, 0, buffer.Length)))
 fileStream.Write(buffer, 0, bytesRead);
```

```csharp
Stream decompressed = entry.Open();
```

### Ver también

* class [RarArchiveEntry](../../rararchiveentry)
* espacio de nombres [Aspose.Zip.Rar](../../rararchiveentry)
* asamblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
