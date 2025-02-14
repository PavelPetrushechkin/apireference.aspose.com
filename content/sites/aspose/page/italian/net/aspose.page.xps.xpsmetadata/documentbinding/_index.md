---
title: DocumentBinding
second_title: Aspose.Page per riferimento all'API .NET
description: Descrive il metodo di associazione. Ogni documento è rilegato separatamente. DocumentBinding e JobBindAllDocuments si escludono a vicenda. Spetta al driver determinare la gestione dei vincoli tra le parole chiave. https//docs.microsoft.com/enus/windows/win32/printdocs/documentbinding
type: docs
weight: 500
url: /it/net/aspose.page.xps.xpsmetadata/documentbinding/
---
## DocumentBinding class

Descrive il metodo di associazione. Ogni documento è rilegato separatamente. DocumentBinding e JobBindAllDocuments si escludono a vicenda. Spetta al driver determinare la gestione dei vincoli tra le parole chiave. https://docs.microsoft.com/en-us/windows/win32/printdocs/documentbinding

```csharp
public sealed class DocumentBinding : Feature, IDocumentPrintTicketItem, IJobPrintTicketItem
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentBinding](documentbinding)(params BindingOption[]) | Crea una nuova istanza. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | Ottiene il nome dell'elemento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/feature/add)(params IFeatureItem[]) | Aggiunge un elenco di elementi alla fine dell'elenco di elementi di questa funzione. Ognuno deve essere a[`Feature`](../feature) , un[`Option`](../option) o a[`Property`](../property) istanza. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [BindingGutter](documentbinding.bindinggutter) | Descrive il modo per specificare il valore della proprietà con punteggio, sia da un valore intero che dal riferimento a parametro. |
| class [BindingOption](documentbinding.bindingoption) | Rappresenta le opzioni del[`DocumentBinding`](../documentbinding) caratteristica. |
| interface [IBindingOptionItem](documentbinding.ibindingoptionitem) | L'interfaccia di qualsiasi[`BindingOption`](../documentbinding.bindingoption) articolo. |

### Guarda anche

* class [Feature](../feature)
* interface [IDocumentPrintTicketItem](../idocumentprintticketitem)
* interface [IJobPrintTicketItem](../ijobprintticketitem)
* spazio dei nomi [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* assemblea [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
