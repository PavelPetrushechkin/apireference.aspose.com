---
title: DOMTokenList
second_title: Aspose.SVG för .NET API Referens
description: Klassen DOMTokenList representerar en uppsättning mellanslagsseparerade tokens. Det indexeras med början med 0 som med JavaScript Arrayobjekt. DOMTokenList är alltid skiftlägeskänslig.
type: docs
weight: 10
url: /sv/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

Klassen DOMTokenList representerar en uppsättning mellanslagsseparerade tokens. Det indexeras med början med 0 som med JavaScript Array-objekt. DOMTokenList är alltid skiftlägeskänslig.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item) { get; } | Returnerar objektet i listan med dess index, eller null om index är större än eller lika med listans längd. |
| [Length](../../aspose.svg.collections/domtokenlist/length) { get; } | Returnerar en ulong som representerar antalet tokens lagrade i den här listan. |
| [Value](../../aspose.svg.collections/domtokenlist/value) { get; set; } | Hämtar eller ställer in värdet för ett motsvarande attribut. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add)(params string[]) | Lägger till de angivna token(erna) till listan. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains)(string) | Returnerar sant om listan innehåller den givna token, annars false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Denna metod används för att hämta ECMAScript-objektType . |
| [Remove](../../aspose.svg.collections/domtokenlist/remove)(params string[]) | Tar bort de angivna token(erna) från listan. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace)(string, string) | Ersätter en befintlig token med en ny token. Gör ingenting om den första token inte finns. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports)(string) | Returnerar sant om en given token finns i det associerade attributets stödda tokens. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle#toggle)(string) | Tar bort token från listan om den finns, eller lägger till token i listan om den inte gör det. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle#toggle_1)(string, bool?) | Tar bort token från listan om den finns, eller lägger till token i listan om den inte gör det. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject)
* namnutrymme [Aspose.Svg.Collections](../../aspose.svg.collections)
* hopsättning [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
