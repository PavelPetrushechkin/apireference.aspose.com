---
title: PPMdCompressionSettings
second_title: Referencia de la API de Aspose.ZIP para .NET
description: Inicializa una nueva instancia delPPMdCompressionSettingsaspose.zip.saving/ppmdcompressionsettings clase.
type: docs
weight: 10
url: /es/net/aspose.zip.saving/ppmdcompressionsettings/ppmdcompressionsettings/
---
## PPMdCompressionSettings(int, int) {#constructor_1}

Inicializa una nueva instancia del[`PPMdCompressionSettings`](../../ppmdcompressionsettings) clase.

```csharp
public PPMdCompressionSettings(int modelOrder, int suballocatorSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| modelOrder | Int32 | Orden del modelo. |
| suballocatorSize | Int32 | El tamaño de la memoria en subasignador de MB puede consumir. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *modelOrder* no está entre 2 y 16. - o -*suballocatorSize* no está entre 1 y 256. |

### Observaciones

Los pedidos de modelos más grandes seguramente darán como resultado una mejor compresión y seguramente más memoria y uso de CPU.

El algoritmo PPMd puede necesitar mucha memoria, especialmente cuando se usa en archivos grandes y/o se usa con un pedido de modelo grande. Si ppmd necesita más memoria de la que le proporciona, la compresión será peor.

### Ejemplos

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new PPMdCompressionSettings(4, 10))))
{
    archive.CreateEntry("data.bin", "data.bin");                   
    archive.Save(zipFile);
}
```

### Ver también

* class [PPMdCompressionSettings](../../ppmdcompressionsettings)
* espacio de nombres [Aspose.Zip.Saving](../../ppmdcompressionsettings)
* asamblea [Aspose.Zip](../../../)

---

## PPMdCompressionSettings() {#constructor}

Inicializa una nueva instancia del[`PPMdCompressionSettings`](../../ppmdcompressionsettings) clase con orden de modelo predeterminado y tamaño de subasignador.

```csharp
public PPMdCompressionSettings()
```

### Observaciones

El orden del modelo predeterminado es 8 y el tamaño del subasignador es 50 MB.

### Ejemplos

```csharp
using (Archive archive = new Archive(new ArchiveEntrySettings(new PPMdCompressionSettings())))
{
    archive.CreateEntry("data.bin", "data.bin");                   
    archive.Save(zipFile);
}
```

### Ver también

* class [PPMdCompressionSettings](../../ppmdcompressionsettings)
* espacio de nombres [Aspose.Zip.Saving](../../ppmdcompressionsettings)
* asamblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
