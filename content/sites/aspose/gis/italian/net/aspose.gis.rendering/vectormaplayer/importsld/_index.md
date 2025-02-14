---
title: ImportSld
second_title: Riferimento API Aspose.GIS per .NET
description: Importa lo stile dal file Styled Layer Descriptor che si trova nel percorso specificato.
type: docs
weight: 60
url: /it/net/aspose.gis.rendering/vectormaplayer/importsld/
---
## ImportSld(string, SldImportOptions) {#importsld_1}

Importa lo stile dal file Styled Layer Descriptor che si trova nel percorso specificato.

```csharp
public void ImportSld(string path, SldImportOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | String | Percorso del file descrittore del livello con stile. |
| options | SldImportOptions | Opzioni di importazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è`null`. |
| XmlException | Si è verificato un errore durante l'analisi dell'XML. |
| FormatException | Nessuno stile SLD è stato trovato nell'XML. |

### Osservazioni

Questo metodo sovrascrive il valore di[`Symbolizer`](../symbolizer) proprietà.

### Guarda anche

* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions)
* class [VectorMapLayer](../../vectormaplayer)
* spazio dei nomi [Aspose.Gis.Rendering](../../vectormaplayer)
* assemblea [Aspose.GIS](../../../)

---

## ImportSld(AbstractPath, SldImportOptions) {#importsld}

Importa lo stile dal file Styled Layer Descriptor che si trova nel percorso specificato.

```csharp
public void ImportSld(AbstractPath path, SldImportOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | AbstractPath | Percorso del file descrittore del livello con stile. |
| options | SldImportOptions | Opzioni di importazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è`null`. |
| XmlException | Si è verificato un errore durante l'analisi dell'XML. |
| FormatException | Nessuno stile SLD è stato trovato nell'XML. |

### Osservazioni

Questo metodo sovrascrive il valore di[`Symbolizer`](../symbolizer) proprietà.

### Guarda anche

* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions)
* class [VectorMapLayer](../../vectormaplayer)
* spazio dei nomi [Aspose.Gis.Rendering](../../vectormaplayer)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
