---
title: TryCreateFromEpsg
second_title: Riferimento API Aspose.GIS per .NET
description: Crea un sistema di riferimento spaziale basato sul codice EPSG specificato.
type: docs
weight: 400
url: /it/net/aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/
---
## SpatialReferenceSystem.TryCreateFromEpsg method

Crea un sistema di riferimento spaziale basato sul codice EPSG specificato.

```csharp
public static bool TryCreateFromEpsg(int epsg, out SpatialReferenceSystem value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| epsg | Int32 | Codice EPSG del sistema di riferimento spaziale. |
| value | SpatialReferenceSystem& | Quando questo metodo ritorna`true` , contiene un SRS con il codice EPSG specificato; in caso contrario, contiene`null` . |

### Valore di ritorno

`true` se il codice EPSG specificato è noto ed è stato creato SRS;`false` altrimenti.

### Guarda anche

* method [CreateFromEpsg](../createfromepsg)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* spazio dei nomi [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
