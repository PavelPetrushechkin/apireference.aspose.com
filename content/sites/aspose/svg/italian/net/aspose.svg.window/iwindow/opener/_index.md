---
title: Opener
second_title: Riferimento API Aspose.SVG per .NET
description: Lattributo IDL di apertura sulloggetto Window al momento della ricezione deve restituire loggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente il suo contesto di navigazione di apertura se presente se è ancora disponibile e se lattuale contesto di navigazione non ha rinnegato il suo apri in caso contrario deve restituire null. Al momento dellimpostazione se il nuovo valore è nullo il contesto di navigazione corrente deve negare il suo apri se il nuovo valore è qualcosaltro lo user agent deve chiamare il metodo interno DefineOwnProperty delloggetto Window passando il nome della proprietà opener come chiave della proprietà e il Property Descriptor  Value value  Writable true Enumerable true Configurable true  come descrittore di proprietà dove value è il nuovo valore.
type: docs
weight: 50
url: /it/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

L'attributo IDL di apertura sull'oggetto Window, al momento della ricezione, deve restituire l'oggetto WindowProxy del contesto di navigazione da cui è stato creato il contesto di navigazione corrente (il suo contesto di navigazione di apertura), se presente, se è ancora disponibile e se l'attuale contesto di navigazione non ha rinnegato il suo apri; in caso contrario, deve restituire null. Al momento dell'impostazione, se il nuovo valore è nullo, il contesto di navigazione corrente deve negare il suo apri; se il nuovo valore è qualcos'altro, lo user agent deve chiamare il metodo interno [[DefineOwnProperty]] dell'oggetto Window, passando il nome della proprietà "opener" come chiave della proprietà, e il Property Descriptor { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } come descrittore di proprietà, dove value è il nuovo valore.

```csharp
public IWindow Opener { get; }
```

### Valore della proprietà

L'apri.

### Guarda anche

* interface [IWindow](../../iwindow)
* spazio dei nomi [Aspose.Svg.Window](../../iwindow)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
