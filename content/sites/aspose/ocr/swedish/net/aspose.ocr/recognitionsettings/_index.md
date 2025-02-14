---
title: RecognitionSettings
second_title: Aspose.OCR för .NET API-referens
description: Inställningar för bildigenkänning. Innehåller element som gör det möjligt att anpassa igenkänningsprocessen.
type: docs
weight: 130
url: /sv/net/aspose.ocr/recognitionsettings/
---
## RecognitionSettings class

Inställningar för bildigenkänning. Innehåller element som gör det möjligt att anpassa igenkänningsprocessen.

```csharp
public class RecognitionSettings
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RecognitionSettings](recognitionsettings)(Language, List&lt;Rectangle&gt;, bool, bool, float, bool, int) | Initierar en ny instans av[`RecognitionSettings`](../recognitionsettings) klass med fullständig uppsättning egenskaper. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllowedCharacters](../../aspose.ocr/recognitionsettings/allowedcharacters) { get; set; } | Tillåtna teckenuppsättningar. Bestämmer vilken typ av tecken som tillåts för igenkänningsresultat. |
| [AutoContrast](../../aspose.ocr/recognitionsettings/autocontrast) { get; set; } | Gör det möjligt att använda en extra kontrastkorrigeringsalgoritm för bilden före igenkänning. |
| [AutoDenoising](../../aspose.ocr/recognitionsettings/autodenoising) { get; set; } | Möjliggör användningen av ytterligare ett neuralt nätverk för att förbättra bilden - reducera brus. Användbart för bilder med skanningsartefakter, distorsion, fläckar, flare, gradienter, främmande element. |
| [AutoSkew](../../aspose.ocr/recognitionsettings/autoskew) { set; } | Hämtar eller ställer in en flagga som indikerar om automatisk snedställningskorrigering ska vara aktiverad. Aktiverad (true) som standard. |
| [DetectAreas](../../aspose.ocr/recognitionsettings/detectareas) { set; } | Hämtar eller ställer in en flagga som indikerar om automatisk detektering av textområden ska vara aktiverad.  Aktiverar modulen för igenkänning av dokumentstruktur. Detta tar mer tid och minne för att bearbeta en bild, men ger mer exakta resultat i komplexa fall. Inaktivera (ställ in på false) för snabbare bildbehandling eller vid bilder med enkel struktur. |
| [DetectAreasMode](../../aspose.ocr/recognitionsettings/detectareasmode) { get; set; } | Gör det möjligt att välja det optimala läget för dokumenttypområden: dokument, foto, vanlig text, kolumn, bild. |
| [IgnoredCharacters](../../aspose.ocr/recognitionsettings/ignoredcharacters) { get; set; } | Ställer in svartlista för igenkänningssymboler. |
| [Language](../../aspose.ocr/recognitionsettings/language) { set; } | Hämtar eller ställer in språket som används för OCR.  Bestämmer alfabetet som används under igenkänning. Flerspråkigt som standard. |
| [LinesFiltration](../../aspose.ocr/recognitionsettings/linesfiltration) { get; set; } | Tillåter att känna igen text i tabellerna (regioner omgivna linjer). |
| [PreprocessingFilters](../../aspose.ocr/recognitionsettings/preprocessingfilters) { get; set; } | Gör det möjligt att förbereda bilden för OCR genom att justera förbehandlingsmetoder. |
| [RecognitionAreas](../../aspose.ocr/recognitionsettings/recognitionareas) { set; } | Hämtar eller ställer in listan över textområden för bearbetning.  Gör det möjligt att manuellt specificera områden med text för mer exakt igenkänning. Om anpassade områden är inställda[`DetectAreas`](./detectareas) och[`AutoSkew`](./autoskew) egenskaper kommer att ignoreras.  Inaktiverar DetectAreas och AutoSkew. |
| [RecognizeSingleLine](../../aspose.ocr/recognitionsettings/recognizesingleline) { set; } | Ställer in en rad bildigenkänning. Inaktiverad (falsk) som standard. Inaktivera alla bearbetningssteg som är associerade med uppdelning i rader. Ställ in denna parameter på true om din bild bara innehåller en rad. Inaktiverar RecognitionAreas-inställningarna så att alla områdesinställningar ignoreras. |
| [SkewAngle](../../aspose.ocr/recognitionsettings/skewangle) { set; } | Hämtar eller ställer in vinkel i grader för bildrotation.  Om du ställer in detta värde inaktiveras[`AutoSkew`](./autoskew) egenskap, så att automatisk skevningskorrigering inte tillämpas. Noll som standard. |
| [ThreadsCount](../../aspose.ocr/recognitionsettings/threadscount) { set; } | Hämtar eller ställer in antalet trådar för bearbetning. Som standard betyder 0 att bilden kommer att bearbetas med antalet trådar lika med ditt antal processorer. ThreadsCount = 1 betyder att bilden kommer att bearbetas i huvudtråden. |
| [ThresholdValue](../../aspose.ocr/recognitionsettings/thresholdvalue) { set; } | Hämtar eller ställer in anpassat tröskelvärde för bildbinarisering. Intervall från 1 till 255. |

### Se även

* namnutrymme [Aspose.OCR](../../aspose.ocr)
* hopsättning [Aspose.OCR](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
