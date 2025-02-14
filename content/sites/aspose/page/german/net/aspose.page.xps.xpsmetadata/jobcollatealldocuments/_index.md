---
title: JobCollateAllDocuments
second_title: Aspose.Page für .NET-API-Referenz
description: Beschreibt die Sortiereigenschaften der Ausgabe. Alle Dokumente in jedem einzelnen Job werden gesammelt. DocumentCollate./documentcollate undJobCollateAllDocuments./jobcollatealldocumentsschließen sich gegenseitig aus. Das Verhalten und die Implementierung ob beide oder nur eines dieser Schlüsselwörter implementiert wird bleibt dem Treiber überlassen. https//docs.microsoft.com/enus/windows/win32/printdocs/jobcollatealldocuments
type: docs
weight: 1140
url: /de/net/aspose.page.xps.xpsmetadata/jobcollatealldocuments/
---
## JobCollateAllDocuments class

Beschreibt die Sortiereigenschaften der Ausgabe. Alle Dokumente in jedem einzelnen Job werden gesammelt. [`DocumentCollate`](../documentcollate) und[`JobCollateAllDocuments`](../jobcollatealldocuments)schließen sich gegenseitig aus. Das Verhalten und die Implementierung, ob beide oder nur eines dieser Schlüsselwörter implementiert wird, bleibt dem Treiber überlassen. https://docs.microsoft.com/en-us/windows/win32/printdocs/jobcollatealldocuments

```csharp
public sealed class JobCollateAllDocuments : Collate, IJobPrintTicketItem
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [JobCollateAllDocuments](jobcollatealldocuments)(params CollateOption[]) | Erstellt eine neue Instanz. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Ruft den Elementnamen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/feature/add)(params IFeatureItem[]) | Fügt eine Liste von Elementen am Ende der Elementliste dieser Funktion hinzu. Jeder muss a sein[`Feature`](../feature) , ein[`Option`](../option) oder ein[`Property`](../property) Instanz. |

### Siehe auch

* class [Collate](../collate)
* interface [IJobPrintTicketItem](../ijobprintticketitem)
* namensraum [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* Montage [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
