---
title: ToLinearGeometry
second_title: Riferimento API Aspose.GIS per .NET
description: Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando limpostazione predefinitatolleranza .
type: docs
weight: 70
url: /it/net/aspose.gis.geometries/curve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando l'impostazione predefinita`tolleranza` .

```csharp
public ILineString ToLinearGeometry()
```

### Valore di ritorno

A[`ILineString`](../../ilinestring) che approssima o equivalente a questa curva. Questo è l'equivalente di[`ToLinearGeometry`](../../icurve/tolineargeometry) con predefinito`tolleranza` . Predefinito`tolleranza` Il valore di s dipende da[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) di questa geometria:  Per la tolleranza SRS prevista è 0,001 metri (in unità SRS) Per la tolleranza SRS geografica è`1e-5` gradi (in unità SRS) Per la tolleranza SRS sconosciuta è`1e-5` Per maggiori dettagli su quali trasformazioni vengono applicate fare riferimento[`ToLinearGeometry`](../../icurve/tolineargeometry) specifica.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Questa geometria non è valida in modo tale che l'operazione non può essere completata. |

### Guarda anche

* interface [ILineString](../../ilinestring)
* class [Curve](../../curve)
* spazio dei nomi [Aspose.Gis.Geometries](../../curve)
* assemblea [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando l'elemento specificato`tolleranza` .

```csharp
public ILineString ToLinearGeometry(double tolerance)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tolerance | Double | Il`tolleranza`usare. Il risultato è garantito inferiore a`tolleranza` lontano dalla geometria curva , a meno che il numero di punti necessari per linearizzare la geometria non ecceda il massimo per quadrante, attualmente pari a 10000 punti. |

### Valore di ritorno

A[`ILineString`](../../ilinestring) che approssima o equivalente a questa curva:  Se questo oggetto è[`ILineString`](../../ilinestring) stesso il risultato è equivalente a questo oggetto Se questo oggetto lo è[`ICircularString`](../../icircularstring) il risultato è la stringa circolare linearizzata con il specificato*tolerance* Se questo oggetto è[`ICompoundCurve`](../../icompoundcurve) - tutte le curve da esso vengono linearizzate e quindi unite[`ILineString`](../../ilinestring)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | `tolleranza` è minore o uguale a`0` . |
| InvalidOperationException | Questa geometria non è valida in modo tale che l'operazione non può essere completata. |

### Guarda anche

* interface [ILineString](../../ilinestring)
* class [Curve](../../curve)
* spazio dei nomi [Aspose.Gis.Geometries](../../curve)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
