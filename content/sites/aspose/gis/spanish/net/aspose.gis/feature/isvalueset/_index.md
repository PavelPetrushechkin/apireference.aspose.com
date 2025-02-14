---
title: IsValueSet
second_title: Referencia de API de Aspose.GIS para .NET
description: Comprueba si el valor del atributo está establecido en esta característica.
type: docs
weight: 90
url: /es/net/aspose.gis/feature/isvalueset/
---
## Feature.IsValueSet method

Comprueba si el valor del atributo está establecido en esta característica.

```csharp
public bool IsValueSet(string attributeName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| attributeName | String | Nombre del atributo. |

### Valor_devuelto

`true` si se establece el valor para el atributo especificado; de lo contrario,`false` .

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | El atributo no está bloqueado. |
| ArgumentException | El atributo con este nombre no existe en esta capa. |
| ArgumentNullException | El nombre del atributo es`null`. |

### Ver también

* class [Feature](../../feature)
* espacio de nombres [Aspose.Gis](../../feature)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
