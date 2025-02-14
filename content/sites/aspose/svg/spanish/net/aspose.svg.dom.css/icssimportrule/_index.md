---
title: ICSSImportRule
second_title: Referencia de API de Aspose.SVG para .NET
description: La interfaz CSSImportRule representa una regla import dentro de una hoja de estilo CSS. La regla import se utiliza para importar reglas de estilo de otras hojas de estilo.
type: docs
weight: 560
url: /es/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

La interfaz CSSImportRule representa una regla @import dentro de una hoja de estilo CSS. La regla @import se utiliza para importar reglas de estilo de otras hojas de estilo.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href) { get; } | La ubicación de la hoja de estilo que se va a importar. El atributo no contendrá el especificador "url(...)" alrededor del URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media) { get; } | Una lista de tipos de medios para los que se puede usar esta hoja de estilo. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet) { get; } | La hoja de estilo a la que hace referencia esta regla, si se ha cargado. El valor de este atributo es nulo si la hoja de estilo aún no se ha cargado o si no se cargará (p. ej., si la hoja de estilo es para un tipo de medio no compatible con el agente de usuario). |

### Ver también

* interface [ICSSRule](../icssrule)
* espacio de nombres [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
