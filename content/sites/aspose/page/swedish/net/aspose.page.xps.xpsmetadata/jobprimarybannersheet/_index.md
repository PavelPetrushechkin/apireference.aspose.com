---
title: JobPrimaryBannerSheet
second_title: Aspose.Page för .NET API-referens
description: Beskriver bannerbladet som ska matas ut för jobbet. Bannerbladet ska matas ut på default PageMediaSize./pagemediasize och använder standardPageMediaType./pagemediatype . Bannerarket bör vara isolerat från resten av jobbet. Detta innebär att eventuella efterbehandlings eller bearbetningsalternativ som JobDuplexAllDocumentsContiguously./jobduplexalldocumentscontiguously JobStapleAllDocuments./jobstaplealldocuments  ellerJobBindAllDocuments./jobbindalldocuments  ska inte inkludera bannerbladet. Bannerbladet ska vara det första arket i jobbet.
type: docs
weight: 1410
url: /sv/net/aspose.page.xps.xpsmetadata/jobprimarybannersheet/
---
## JobPrimaryBannerSheet class

Beskriver bannerbladet som ska matas ut för jobbet. Bannerbladet ska matas ut på default [`PageMediaSize`](../pagemediasize) och använder standard[`PageMediaType`](../pagemediatype) . Bannerarket bör vara isolerat från resten av jobbet. Detta innebär att eventuella efterbehandlings- eller bearbetningsalternativ (som [`JobDuplexAllDocumentsContiguously`](../jobduplexalldocumentscontiguously) ,[`JobStapleAllDocuments`](../jobstaplealldocuments) , eller[`JobBindAllDocuments`](../jobbindalldocuments) ) ska inte inkludera bannerbladet. Bannerbladet ska vara det första arket i jobbet.

```csharp
public sealed class JobPrimaryBannerSheet : Feature, IJobPrintTicketItem
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [JobPrimaryBannerSheet](jobprimarybannersheet)(params BannerSheetOption[]) | Skapar en ny instans. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Hämtar elementets namn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/feature/add)(params IFeatureItem[]) | Lägger till en lista med objekt i slutet av denna funktions objektlista. Var och en måste vara en[`Feature`](../feature) , en[`Option`](../option) eller a[`Property`](../property) instans. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [BannerSheetOption](jobprimarybannersheet.bannersheetoption) | Representerar alternativ för[`JobPrimaryBannerSheet`](../jobprimarybannersheet) feature. |

### Se även

* class [Feature](../feature)
* interface [IJobPrintTicketItem](../ijobprintticketitem)
* namnutrymme [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* hopsättning [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
