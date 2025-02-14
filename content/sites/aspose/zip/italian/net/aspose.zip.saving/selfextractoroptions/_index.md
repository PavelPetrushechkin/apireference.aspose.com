---
title: SelfExtractorOptions
second_title: Riferimento API Aspose.ZIP per .NET
description: Opzioni per la creazione dellarchivio eseguibile autoestraente.
type: docs
weight: 430
url: /it/net/aspose.zip.saving/selfextractoroptions/
---
## SelfExtractorOptions class

Opzioni per la creazione dell'archivio eseguibile autoestraente.

```csharp
public class SelfExtractorOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SelfExtractorOptions](selfextractoroptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CloseWindowOnExtraction](../../aspose.zip.saving/selfextractoroptions/closewindowonextraction) { get; set; } | Ottiene o imposta un valore che indica se la finestra dell'estrattore deve essere chiusa o meno all'estrazione. |
| [ExtractorTitle](../../aspose.zip.saving/selfextractoroptions/extractortitle) { get; set; } | Ottiene o imposta il titolo della finestra dell'estrattore. |
| [RunAfterExtraction](../../aspose.zip.saving/selfextractoroptions/runafterextraction) { get; set; } | Ottiene o imposta un programma da eseguire al termine dell'estrazione dell'archivio. |
| [TitleIcon](../../aspose.zip.saving/selfextractoroptions/titleicon) { get; set; } | Ottiene o imposta il percorso dell'icona del titolo per le finestre principali dell'applicazione di estrazione. |

### Osservazioni

Archivio autoestraente non componibile con licenza a consumo:[`MeteredLicense`](../../aspose.zip/meteredlicense) .

### Esempi

```csharp
using (FileStream zipFile = File.Open("archive.exe", FileMode.Create))
{
    using (var archive = new Archive())
    {
        archive.CreateEntry("entry.bin", "data.bin");
        var sfxOptions = new SelfExtractorOptions() { ExtractorTitle = "Extractor", CloseWindowOnExtraction = true, TitleIcon = "C:\pictorgam.ico" };
        archive.Save(zipFile, new ArchiveSaveOptions() { SelfExtractorOptions = sfxOptions });
    }
}
```

### Guarda anche

* spazio dei nomi [Aspose.Zip.Saving](../../aspose.zip.saving)
* assemblea [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
