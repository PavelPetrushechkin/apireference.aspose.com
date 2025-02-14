---
title: Extract
second_title: Aspose.ZIP för .NET API-referens
description: Extraherar posten till filsystemet med den angivna sökvägen.
type: docs
weight: 20
url: /sv/net/aspose.zip.wim/wimfileentry/extract/
---
## Extract(string) {#extract}

Extraherar posten till filsystemet med den angivna sökvägen.

```csharp
public FileSystemInfo Extract(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen till destinationsfilen. Om filen redan finns kommer den att skrivas över. |

### Returvärde

Filinformationen för den sammansatta filen.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *path* är inget. |
| SecurityException | Den som ringer har inte den behörighet som krävs för att få åtkomst. |
| ArgumentException | De*path* är tom, innehåller bara blanksteg eller innehåller ogiltiga tecken. |
| UnauthorizedAccessException | Tillgång till fil*path* är nekad. |
| PathTooLongException | Den angivna*path*, filnamn eller båda överskrider den systemdefinierade maximala längden. Till exempel, på Windows-baserade plattformar måste sökvägar vara mindre än 248 tecken och filnamn måste vara mindre än 260 tecken. |
| NotSupportedException | Arkivera kl*path* innehåller ett kolon (:) i mitten av strängen. |

### Exempel

```csharp
using (var archive = new WimArchive("archive.wim"))
{
    archive.Images[0].RootDirectory.Files[0].Extract("data.bin");
}
```

### Se även

* class [WimFileEntry](../../wimfileentry)
* namnutrymme [Aspose.Zip.Wim](../../wimfileentry)
* hopsättning [Aspose.Zip](../../../)

---

## Extract(Stream) {#extract_1}

Extraherar posten till den tillhandahållna strömmen.

```csharp
public void Extract(Stream destination)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destination | Stream | Destinationsström. Måste vara skrivbart. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | *destination* stöder inte skrivande. |

### Exempel

Extrahera en post i wim-arkivet.

```csharp
using (var archive = new WimArchive("archive.wim"))
{
    archive.Images[0].RootDirectory.Files[0].Extract(httpResponseStream);
}
```

### Se även

* class [WimFileEntry](../../wimfileentry)
* namnutrymme [Aspose.Zip.Wim](../../wimfileentry)
* hopsättning [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
