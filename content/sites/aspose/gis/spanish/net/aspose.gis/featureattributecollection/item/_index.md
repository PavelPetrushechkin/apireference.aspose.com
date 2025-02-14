---
title: Item
second_title: Referencia de API de Aspose.GIS para .NET
description: Obtiene o establece elFeatureAttributeaspose.gis/featureattribute en el índice especificado.
type: docs
weight: 30
url: /es/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

Obtiene o establece el[`FeatureAttribute`](../../featureattribute) en el índice especificado.

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice de base cero del atributo que se va a obtener o establecer. |

### Valor_devuelto

El atributo en el índice especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El índice está fuera de rango. |
| InvalidOperationException | Intento de modificar una colección bloqueada. |

### Ver también

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* espacio de nombres [Aspose.Gis](../../featureattributecollection)
* asamblea [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

Obtiene o establece el[`FeatureAttribute`](../../featureattribute) con un nombre especificado.

```csharp
public FeatureAttribute this[string name] { get; }
```

| Parámetro | Descripción |
| --- | --- |
| name | Nombre de los atributos. |

### Valor_devuelto

El atributo con el nombre especificado, o`null` si no se encuentra.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El nombre del atributo es`null`. |

### Ver también

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* espacio de nombres [Aspose.Gis](../../featureattributecollection)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
