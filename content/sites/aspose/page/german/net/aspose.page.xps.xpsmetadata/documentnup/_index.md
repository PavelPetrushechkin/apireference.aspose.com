---
title: DocumentNUp
second_title: Aspose.Page für .NET-API-Referenz
description: Beschreibt die Ausgabe und das Format mehrerer logischer Seiten auf einem einzigen physischen Blatt. Jedes Dokument wird separat zusammengestellt. undJobNUpAllDocumentsContiguously./jobnupalldocumentscontiguously schließen sich gegenseitig aus. Es ist Sache des Treibers die Behandlung von Einschränkungen zwischen diesen Schlüsselwörtern zu bestimmen. https//docs.microsoft.com/enus/windows/win32/printdocs/documentnup
type: docs
weight: 680
url: /de/net/aspose.page.xps.xpsmetadata/documentnup/
---
## DocumentNUp class

Beschreibt die Ausgabe und das Format mehrerer logischer Seiten auf einem einzigen physischen Blatt. Jedes Dokument wird separat zusammengestellt. und[`JobNUpAllDocumentsContiguously`](../jobnupalldocumentscontiguously) schließen sich gegenseitig aus. Es ist Sache des Treibers, die Behandlung von Einschränkungen zwischen diesen Schlüsselwörtern zu bestimmen. https://docs.microsoft.com/en-us/windows/win32/printdocs/documentnup

```csharp
DocumentNUp
```

```csharp
public sealed class DocumentNUp : NUp, IDocumentPrintTicketItem, IJobPrintTicketItem
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DocumentNUp](documentnup)(params INUpItem[]) | Erstellt eine neue Instanz. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Ruft den Elementnamen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/feature/add)(params IFeatureItem[]) | Fügt eine Liste von Elementen am Ende der Elementliste dieser Funktion hinzu. Jeder muss a sein[`Feature`](../feature) , ein[`Option`](../option) oder ein[`Property`](../property) Instanz. |
| [AddPagesPerSheetOption](../../aspose.page.xps.xpsmetadata/documentnup/addpagespersheetoption)(int) | Fügt und Option mit a hinzu Wert der bewerteten Eigenschaft. Gibt die Anzahl der logischen Seiten pro physischem Blatt an. |

### Siehe auch

* class [NUp](../nup)
* interface [IDocumentPrintTicketItem](../idocumentprintticketitem)
* interface [IJobPrintTicketItem](../ijobprintticketitem)
* namensraum [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* Montage [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
