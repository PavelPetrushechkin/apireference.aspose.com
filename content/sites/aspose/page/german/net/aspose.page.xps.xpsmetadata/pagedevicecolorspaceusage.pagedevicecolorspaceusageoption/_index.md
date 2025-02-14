---
title: PageDeviceColorSpaceUsage.PageDeviceColorSpaceUsageOption
second_title: Aspose.Page für .NET-API-Referenz
description: Beschreibt diePageDeviceColorSpaceUsage./pagedevicecolorspaceusage Funktionsoptionen.
type: docs
weight: 1880
url: /de/net/aspose.page.xps.xpsmetadata/pagedevicecolorspaceusage.pagedevicecolorspaceusageoption/
---
## PageDeviceColorSpaceUsage.PageDeviceColorSpaceUsageOption class

Beschreibt die[`PageDeviceColorSpaceUsage`](../pagedevicecolorspaceusage) Funktionsoptionen.

```csharp
public sealed class PageDeviceColorSpaceUsageOption : Option
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Ruft den Elementnamen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/option/add)(params IOptionItem[]) | Fügt eine Liste von Elementen am Ende der Elementliste dieser Option hinzu. Jeder muss a sein[`ScoredProperty`](../scoredproperty) oder[`Property`](../property) Instanz. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static [MatchToDefault](../../aspose.page.xps.xpsmetadata/pagedevicecolorspaceusageoption/matchtodefault) | Wenn das Gerät feststellt, dass das von der angegebene Profil[`PageDeviceColorSpaceProfileURI`](../pagedevicecolorspaceprofileuri) parameter kann als Gerätefarbraumprofil verwendet werden, alle Elemente, die dasselbe Profil verwenden, werden so behandelt, als seien sie bereits im Gerätefarbraum spezifiziert . Alle anderen Elemente MÜSSEN das für dieses Element angegebene Profil verwenden. Wenn das Profil nicht als Gerätefarbraumprofil verwendet werden kann, MÜSSEN Elemente, die das Profil verwenden, wie alle anderen Elemente, die das Farbprofil verwenden, farblich verwaltet werden. |
| static [OverrideDeviceDefault](../../aspose.page.xps.xpsmetadata/pagedevicecolorspaceusageoption/overridedevicedefault) | Wenn das durch den Parameter PageDeviceColorSpaceProfileURI angegebene Profil eine Anzahl von Kanälen hat, die der Anzahl der Primärfarben des Geräts entspricht, SOLLTE es anstelle des geräteinternen Farbmanagements für alle Elemente verwendet werden. Elemente, die dieses Profil verwenden, werden als in Gerätefarbe angenommen Leerzeichen und wird nicht weiter farblich verwaltet. |

### Siehe auch

* class [Option](../option)
* class [PageDeviceColorSpaceUsage](../pagedevicecolorspaceusage)
* namensraum [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* Montage [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
