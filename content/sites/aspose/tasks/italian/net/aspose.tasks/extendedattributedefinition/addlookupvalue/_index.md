---
title: AddLookupValue
second_title: Riferimento all'API di Aspose.Tasks per .NET
description: Aggiunge un valore allelenco di ricerca interno. Questo è un modo preferibile per le manipolazioni con ilValueListaspose.tasks/extendedattributedefinition/valuelist .
type: docs
weight: 290
url: /it/net/aspose.tasks/extendedattributedefinition/addlookupvalue/
---
## ExtendedAttributeDefinition.AddLookupValue method

Aggiunge un valore all'elenco di ricerca interno. Questo è un modo preferibile per le manipolazioni con il[`ValueList`](../valuelist) .

```csharp
public void AddLookupValue(Value value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | Value | Valore da aggiungere nella ricerca. |

### Osservazioni

Questo metodo funziona solo per[`ExtendedAttributeDefinition`](../../extendedattributedefinition) istanze che hanno[`CalculationType`](../calculationtype) è uguale aLookup .

### Esempi

Usa questo codice per aggiungere un nuovo valore all'elenco di ricerca:

```csharp
taskTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
```

### Guarda anche

* class [Value](../../value)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* spazio dei nomi [Aspose.Tasks](../../extendedattributedefinition)
* assemblea [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
