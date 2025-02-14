---
title: Identifier
second_title: Riferimento API Aspose.GIS per .NET
description: Rappresenta un identificatore  un riferimento alla descrizione esterna di un oggetto. Se crei un SRS da WKTIdentifier./identifier corrisponde alla parola chiave AUTHORITY.
type: docs
weight: 2060
url: /it/net/aspose.gis.spatialreferencing/identifier/
---
## Identifier class

Rappresenta un identificatore - un riferimento alla descrizione esterna di un oggetto. Se crei un SRS da WKT,[`Identifier`](../identifier) corrisponde alla parola chiave "AUTHORITY".

```csharp
public class Identifier : IEquatable<Identifier>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Identifier](identifier)(string, string) | Crea nuova istanza. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AuthorityName](../../aspose.gis.spatialreferencing/identifier/authorityname) { get; } | Un nome di autorità, che ha dato un[`AuthorityUniqueIdentifier`](./authorityuniqueidentifier) . |
| [AuthorityUniqueIdentifier](../../aspose.gis.spatialreferencing/identifier/authorityuniqueidentifier) { get; } | Un modo unico per rappresentare un oggetto all'interno di a[`AuthorityName`](./authorityname) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Epsg](../../aspose.gis.spatialreferencing/identifier/epsg)(int) | Crea un nuovo identificatore che rappresenta l'identificatore EPSG con il codice*epsgCode* . |
| [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals)(Identifier) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| override [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals_1)(object) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [GetEpsgCode](../../aspose.gis.spatialreferencing/identifier/getepsgcode)() | Se questo oggetto rappresenta un identificatore EPSG valido (ad es. - il nome dell'autorità è "EPSG" e l'identificatore univoco dell'autorità è intero) - restituirlo. Altrimenti - restituisce -1. |
| override [GetHashCode](../../aspose.gis.spatialreferencing/identifier/gethashcode)() | Serve come funzione hash predefinita. |
| [operator ==](../../aspose.gis.spatialreferencing/identifier/op_equality) | Implementa l'operatore ==. |
| [operator !=](../../aspose.gis.spatialreferencing/identifier/op_inequality) | Implementa l'operatore !=. |

### Esempi

Il sistema di riferimento spaziale WGS 84 ha il codice EPSG 4326, quindi potrebbe contenere identificatore: WGS 84 Ellissoide ha il codice EPSG 7030 e potrebbe contenere identificatore:

```csharp
new  {  = "EPSG",  = 4326 };
```

```csharp
new  {  = "EPSG",  = 7030 };
```

### Guarda anche

* spazio dei nomi [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* assemblea [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
