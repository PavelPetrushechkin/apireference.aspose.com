---
title: ObjectIdFieldName
second_title: Riferimento API Aspose.GIS per .NET
description: Nome del campo ID oggetto.
type: docs
weight: 60
url: /it/net/aspose.gis.formats.filegdb/filegdboptions/objectidfieldname/
---
## FileGdbOptions.ObjectIdFieldName property

Nome del campo ID oggetto.

```csharp
public string ObjectIdFieldName { get; set; }
```

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Il valore non è un nome di campo valido. Un nome campo valido deve:  Non essere`null` e non vuotoInizia con una lettera latina o un trattino bassoContengono solo lettere latine, cifre o trattini bassi |

### Osservazioni

Questa è un'opzione di creazione e non influisce sulla lettura. Definisce il nome del campo ID oggetto (colonna). Il valore predefinito è "OBJECTID". Se qualsiasi attributo in[`Attributes`](../../../aspose.gis/vectorlayer/attributes) ha nome uguale al valore di questa proprietà, quindi questo attributo viene rinominato.

### Guarda anche

* class [FileGdbOptions](../../filegdboptions)
* spazio dei nomi [Aspose.Gis.Formats.FileGdb](../../filegdboptions)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
