---
title: GzipArchive
second_title: Aspose.ZIP für .NET-API-Referenz
description: Diese Klasse repräsentiert eine gzipArchivdatei. Verwenden Sie es um gzipArchive zu erstellen oder zu extrahieren.
type: docs
weight: 160
url: /de/net/aspose.zip.gzip/gziparchive/
---
## GzipArchive class

Diese Klasse repräsentiert eine gzip-Archivdatei. Verwenden Sie es, um gzip-Archive zu erstellen oder zu extrahieren.

```csharp
public class GzipArchive : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GzipArchive](gziparchive#constructor)() | Initialisiert eine neue Instanz von[`GzipArchive`](../gziparchive) Klasse zum Komprimieren vorbereitet. |
| [GzipArchive](gziparchive#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz von[`GzipArchive`](../gziparchive) Klasse zum Dekomprimieren vorbereitet. |
| [GzipArchive](gziparchive#constructor_2)(string, bool) | Initialisiert eine neue Instanz von[`GzipArchive`](../gziparchive) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Name](../../aspose.zip.gzip/gziparchive/name) { get; } | Name der Originaldatei. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.zip.gzip/gziparchive/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [Extract](../../aspose.zip.gzip/gziparchive/extract)(Stream) | Extrahiert das Archiv in den bereitgestellten Stream. |
| [Open](../../aspose.zip.gzip/gziparchive/open)() | Öffnet das Archiv zum Extrahieren und stellt einen Stream mit Archivinhalten bereit. |
| [Save](../../aspose.zip.gzip/gziparchive/save#save)(Stream) | Speichert das Archiv im bereitgestellten Stream. |
| [Save](../../aspose.zip.gzip/gziparchive/save#save_1)(string) | Speichert das Archiv in der bereitgestellten Zieldatei. |
| [SetSource](../../aspose.zip.gzip/gziparchive/setsource#setsource_1)(FileInfo) | Legt den Inhalt fest, der innerhalb des Archivs komprimiert werden soll. |
| [SetSource](../../aspose.zip.gzip/gziparchive/setsource#setsource_2)(Stream) | Legt den Inhalt fest, der innerhalb des Archivs komprimiert werden soll. |
| [SetSource](../../aspose.zip.gzip/gziparchive/setsource#setsource_3)(string) | Legt den Inhalt fest, der innerhalb des Archivs komprimiert werden soll. |
| [SetSource](../../aspose.zip.gzip/gziparchive/setsource#setsource)(TarArchive) | Legt den Inhalt fest, der innerhalb des Archivs komprimiert werden soll. |

### Bemerkungen

Der Gzip-Komprimierungsalgorithmus basiert auf dem DEFLATE-Algorithmus, der eine Kombination aus LZ77- und Huffman-Codierung ist.

### Siehe auch

* namensraum [Aspose.Zip.Gzip](../../aspose.zip.gzip)
* Montage [Aspose.Zip](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
