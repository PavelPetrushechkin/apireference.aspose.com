---
title: CreateFilterRule
second_title: Riferimento API Aspose.GIS per .NET
description: Crea una nuova regola che applica un simbolizzatore alla funzione ogni volta che supera il filtro.
type: docs
weight: 20
url: /it/net/aspose.gis.rendering.symbolizers/rule/createfilterrule/
---
## Rule.CreateFilterRule method

Crea una nuova regola che applica un simbolizzatore alla funzione ogni volta che supera il filtro.

```csharp
public static Rule CreateFilterRule(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filter | Func`2 | Determina quando utilizzare il simbolizzatore. |
| symbolizer | VectorSymbolizer | Simbolizzatore da applicare. |

### Valore di ritorno

Nuovo oggetto Regola.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Il filtro è`null`. |

### Guarda anche

* class [Feature](../../../aspose.gis/feature)
* class [VectorSymbolizer](../../vectorsymbolizer)
* class [Rule](../../rule)
* spazio dei nomi [Aspose.Gis.Rendering.Symbolizers](../../rule)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
