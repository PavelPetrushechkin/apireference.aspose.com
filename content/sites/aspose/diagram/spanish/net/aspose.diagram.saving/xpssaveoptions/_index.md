---
title: XPSSaveOptions
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Permite especificar opciones adicionales al renderizar páginas de diagramas a XPS.
type: docs
weight: 3510
url: /es/net/aspose.diagram.saving/xpssaveoptions/
---
## XPSSaveOptions class

Permite especificar opciones adicionales al renderizar páginas de diagramas a XPS.

```csharp
public class XPSSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XPSSaveOptions](xpssaveoptions)() | Inicializa una nueva instancia de esta clase que se puede usar para guardar un documento en el[`XPS`](../../aspose.diagram/savefileformat)formato. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Cuando los caracteres en el diagrama son Unicode y no están configurados con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en pdf, imagen o XPS. Establezca la fuente predeterminada como MingLiu o MS Gothic para mostrar estos personajes. |
| [ExportHiddenPage](../../aspose.diagram.saving/xpssaveoptions/exporthiddenpage) { get; set; } | Define si es necesario exportar la página oculta o no. |
| [PageCount](../../aspose.diagram.saving/xpssaveoptions/pagecount) { get; set; } | Obtiene o establece el número de páginas para representar en XPS. El valor predeterminado es MaxValue, lo que significa que se representarán todas las páginas del diagrama. |
| [PageIndex](../../aspose.diagram.saving/xpssaveoptions/pageindex) { get; set; } | Obtiene o establece el índice basado en 0 de la primera página que se va a representar. El valor predeterminado es 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/xpssaveoptions/saveforegroundpagesonly) { get; set; } | Especifica si todas las páginas se guardarán en imagen o solo en primer plano. |
| override [SaveFormat](../../aspose.diagram.saving/xpssaveoptions/saveformat) { get; set; } | Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se usa este objeto de opciones de guardado. Puede ser[`XPS`](../../aspose.diagram/savefileformat) solo. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Obtiene o establece la devolución de llamada de advertencia. |

### Ver también

* class [SaveOptions](../saveoptions)
* espacio de nombres [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
