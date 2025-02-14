---
title: ParallelOptions
second_title: Aspose.ZIP for .NET API Referansı
description: Paralel sıkıştırma seçenekleri.
type: docs
weight: 420
url: /tr/net/aspose.zip.saving/paralleloptions/
---
## ParallelOptions class

Paralel sıkıştırma seçenekleri.

```csharp
public class ParallelOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ParallelOptions](paralleloptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AvailableMemorySize](../../aspose.zip.saving/paralleloptions/availablememorysize) { get; set; } | Diske değiştirmeden sıkıştırılmış girişleri barındırmak için megabayt cinsinden bellek tahminini alır veya ayarlar. Bu değer yalnızca şu durumlarda anlamlıdır:[`ParallelCompressInMemory`](./parallelcompressinmemory) ayar varAuto mod. |
| [ParallelCompressInMemory](../../aspose.zip.saving/paralleloptions/parallelcompressinmemory) { get; set; } | Paralel yaklaşımın nasıl kullanılacağını gösteren değeri alır veya ayarlar. |

### Notlar

Bu seçenekler, birkaç CPU çekirdeği tarafından eşzamanlı sıkıştırmayı yönetir.

### Örnekler

```csharp
using (var archive = new Archive())
{
    archive.CreateEntries("DirToCompress");
    archive.Save("archive.zip", new ArchiveSaveOptions() { ParallelOptions = new ParallelOptions { ParallelCompressInMemory = mode, AvailableMemorySize = 4000 } });
}
```

### Ayrıca bakınız

* ad alanı [Aspose.Zip.Saving](../../aspose.zip.saving)
* toplantı [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
