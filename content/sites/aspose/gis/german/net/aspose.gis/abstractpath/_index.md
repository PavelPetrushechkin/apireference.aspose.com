---
title: AbstractPath
second_title: Aspose.GIS für .NET-API-Referenz
description: EinAbstrakterPfad ist eine Basisklasse für Klassen die einen eindeutigen Ort in einer Umgebung angeben die einem Dateisystem ähnlich ist wie unter anderem ein lokales Dateisystem ein entfernter Dateispeicher oder ein ZIPArchiv.
type: docs
weight: 10
url: /de/net/aspose.gis/abstractpath/
---
## AbstractPath class

Ein`AbstrakterPfad` ist eine Basisklasse für Klassen, die einen eindeutigen Ort in einer Umgebung angeben, die einem Dateisystem ähnlich ist, wie unter anderem ein lokales Dateisystem, ein entfernter Dateispeicher oder ein ZIP-Archiv.

```csharp
public abstract class AbstractPath
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [Location](../../aspose.gis/abstractpath/location) { get; } | Ruft eine Zeichenfolgendarstellung des Speicherorts davon ab`AbstrakterPfad` . |
| abstract [Separator](../../aspose.gis/abstractpath/separator) { get; } | Ruft ein Trennzeichen ab, das verwendet wird, um Verzeichnisebenen der zu trennen[`Location`](./location) Schnur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromLocalPath](../../aspose.gis/abstractpath/fromlocalpath)(string) | Erstellt eine[`AbstractPath`](../abstractpath) das einen Speicherort im lokalen Dateisystem darstellt. |
| static [FromStream](../../aspose.gis/abstractpath/fromstream)(Stream) | Erstellt eine[`AbstractPath`](../abstractpath) von einemStream . |
| virtual [Combine](../../aspose.gis/abstractpath/combine)(string) | Kombiniert dies[`AbstractPath`](../abstractpath) mit angegebenen Pfadkomponenten. |
| abstract [Delete](../../aspose.gis/abstractpath/delete)() | Löscht eine Datei, auf die dieser Pfad zeigt. |
| [GetExtension](../../aspose.gis/abstractpath/getextension)() | Gibt die Erweiterung davon zurück[`AbstractPath`](../abstractpath) . |
| [GetFileName](../../aspose.gis/abstractpath/getfilename)() | Gibt den Dateinamen und die Erweiterung davon zurück[`AbstractPath`](../abstractpath) . |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension)() | Gibt den Dateinamen davon zurück[`AbstractPath`](../abstractpath) ohne die Erweiterung. |
| abstract [IsFile](../../aspose.gis/abstractpath/isfile)() | Ruft einen Wert ab, der angibt, ob dieser Pfad auf eine vorhandene Datei verweist, die zum Lesen geöffnet werden kann. |
| abstract [ListDirectory](../../aspose.gis/abstractpath/listdirectory)() | Gibt darin befindliche Pfade zurück`AbstrakterPfad` , wenn es sich um ein Verzeichnis handelt. |
| abstract [Open](../../aspose.gis/abstractpath/open)(FileAccess) | Öffnet dies`AbstrakterPfad`als Datei. |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension)(string) | Gibt eine neue zurück[`AbstractPath`](../abstractpath) mit der Dateierweiterung auf den angegebenen Wert geändert. |

### Bemerkungen

Ein`AbstrakterPfad` kann einen Speicherort in einem lokalen Dateisystem, einen Speicherort in einem Remote-Dateisystem oder einen externen Speicher wie Azure Blob Storage usw. angeben. Der Speicherort kann auf ein vorhandenes oder nicht vorhandenes dateiähnliches Objekt oder verzeichnisähnliches Objekt verweisen oder jede andere sinnvolle Bedeutung für die Umgebung haben, zu der es gehört. Als Beispiel ein`AbstrakterPfad` Ein Erbe, der einen Ort im lokalen Dateisystem darstellt, kann auf eine vorhandene -Datei, ein Verzeichnis oder auf einen Ort im Dateisystem zeigen, der noch nicht erstellt wurde. Um einen neuen Dateisystem-ähnlichen Speicher verfügbar zu machen`Aspose.GIS` sollte man diese Klasse erben und ihre abstrakten Methoden implementieren.

### Siehe auch

* namensraum [Aspose.Gis](../../aspose.gis)
* Montage [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
