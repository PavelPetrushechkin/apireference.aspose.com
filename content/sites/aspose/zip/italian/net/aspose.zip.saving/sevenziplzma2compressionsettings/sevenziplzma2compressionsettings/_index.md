---
title: SevenZipLZMA2CompressionSettings
second_title: Riferimento API Aspose.ZIP per .NET
description: Istanzia le impostazioni per il metodo di compressione LZMA2 allinterno dellarchivio 7z.
type: docs
weight: 10
url: /it/net/aspose.zip.saving/sevenziplzma2compressionsettings/sevenziplzma2compressionsettings/
---
## SevenZipLZMA2CompressionSettings(int) {#constructor}

Istanzia le impostazioni per il metodo di compressione LZMA2 all'interno dell'archivio 7z.

```csharp
public SevenZipLZMA2CompressionSettings(int dictionarySize = 16777216)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictionarySize | Int32 | La dimensione del buffer della cronologia deve essere compresa tra 4096 e 1073741824. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *dictionarySize* è troppo grande o troppo piccolo. |

### Osservazioni

Più grande è il dizionario, migliore è solitamente il rapporto di compressione, ma dizionari più grandi dei dati non compressi sono uno spreco di RAM.

### Guarda anche

* class [SevenZipLZMA2CompressionSettings](../../sevenziplzma2compressionsettings)
* spazio dei nomi [Aspose.Zip.Saving](../../sevenziplzma2compressionsettings)
* assemblea [Aspose.Zip](../../../)

---

## SevenZipLZMA2CompressionSettings(int, int) {#constructor_1}

Istanzia le impostazioni per il metodo di compressione LZMA2 all'interno dell'archivio 7z.

```csharp
public SevenZipLZMA2CompressionSettings(int dictionarySize, int fastBytes = 32)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictionarySize | Int32 | La dimensione del buffer della cronologia deve essere compresa tra 4096 e 1073741824. |
| fastBytes | Int32 | Controlla il numero di byte veloci utilizzati dai compressori LZMA2. Un numero maggiore di byte veloci può fornire un rapporto di compressione migliore a scapito della velocità di compressione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *dictionarySize* è troppo grande o troppo piccolo, o*fastBytes* è troppo grande o troppo piccolo. |

### Osservazioni

Più grande è il dizionario, migliore è solitamente il rapporto di compressione, ma dizionari più grandi dei dati non compressi sono uno spreco di RAM.

### Guarda anche

* class [SevenZipLZMA2CompressionSettings](../../sevenziplzma2compressionsettings)
* spazio dei nomi [Aspose.Zip.Saving](../../sevenziplzma2compressionsettings)
* assemblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
