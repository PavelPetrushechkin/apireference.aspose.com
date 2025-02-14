---
title: XarFileEntry
second_title: Referencia de la API de Aspose.ZIP para .NET
description: Representa la entrada del archivo dentro del archivo xar.
type: docs
weight: 710
url: /es/net/aspose.zip.xar/xarfileentry/
---
## XarFileEntry class

Representa la entrada del archivo dentro del archivo xar.

```csharp
public abstract class XarFileEntry : XarEntry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreationTime](../../aspose.zip.xar/xarentry/creationtime) { get; } | Obtiene la hora de creación del archivo o directorio. |
| [FullPath](../../aspose.zip.xar/xarentry/fullpath) { get; } | Obtiene la ruta completa de la entrada dentro del archivo. |
| [IsDirectory](../../aspose.zip.xar/xarentry/isdirectory) { get; } | Obtiene un valor que indica si la entrada representa el directorio. |
| [LastAccessTime](../../aspose.zip.xar/xarentry/lastaccesstime) { get; } | Obtiene la hora del último acceso al archivo o directorio. |
| [LastWriteTime](../../aspose.zip.xar/xarentry/lastwritetime) { get; } | Obtiene la hora de modificación del archivo o directorio. |
| abstract [Length](../../aspose.zip.xar/xarfileentry/length) { get; } | Obtiene la longitud de la entrada en bytes. |
| [Name](../../aspose.zip.xar/xarentry/name) { get; } | Obtiene el nombre de la entrada dentro del archivo. |
| [Parent](../../aspose.zip.xar/xarentry/parent) { get; } | Obtiene el directorio padre al que pertenece la entrada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Extract](../../aspose.zip.xar/xarfileentry/extract#extract_1)(Stream) | Extrae la entrada al flujo proporcionado. |
| abstract [Extract](../../aspose.zip.xar/xarfileentry/extract#extract)(string) | Extrae la entrada al sistema de archivos por la ruta proporcionada. |
| abstract [Open](../../aspose.zip.xar/xarfileentry/open)() | Abre la entrada para la extracción y proporciona una secuencia con el contenido de la entrada. |
| override [ToString](../../aspose.zip.xar/xarentry/tostring)() |  |

### Ver también

* class [XarEntry](../xarentry)
* espacio de nombres [Aspose.Zip.Xar](../../aspose.zip.xar)
* asamblea [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
