---
title: IAlgorithmT
second_title: Riferimento all'API di Aspose.Tasks per .NET
description: Rappresenta un algoritmo che può essere applicato a un elenco di oggettiT .
type: docs
weight: 2370
url: /it/net/aspose.tasks.util/ialgorithm-1/
---
## IAlgorithm&lt;T&gt; interface

Rappresenta un algoritmo che può essere applicato a un elenco di oggetti*T* .

```csharp
public interface IAlgorithm<in T>
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di oggetto a cui applicare l'interfaccia del metodo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Alg](../../aspose.tasks.util/ialgorithm`1/alg)(T, int) | Elabora un oggetto nell'elenco. Chiamato dopo[`PreAlg`](./prealg) ; |
| [PostAlg](../../aspose.tasks.util/ialgorithm`1/postalg)(T, int) | Chiamato dopo l'elaborazione di un oggetto. |
| [PreAlg](../../aspose.tasks.util/ialgorithm`1/prealg)(T, int) | Chiamato prima dell'elaborazione di un oggetto. |

### Guarda anche

* spazio dei nomi [Aspose.Tasks.Util](../../aspose.tasks.util)
* assemblea [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
