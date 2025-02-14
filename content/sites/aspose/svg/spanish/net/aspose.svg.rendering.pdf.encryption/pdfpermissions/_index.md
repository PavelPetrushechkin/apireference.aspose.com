---
title: PdfPermissions
second_title: Referencia de API de Aspose.SVG para .NET
description: Esta enumeración representa los permisos del usuario para un pdf.
type: docs
weight: 2890
url: /es/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Esta enumeración representa los permisos del usuario para un pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PrintDocument | `4` | (Manejadores de seguridad de revisión 2) Imprime el documento. (Controladores de seguridad de revisión 3 o superior) Imprima el documento (posiblemente no con el nivel de calidad más alto, dependiendo de si también se ha configurado Calidad de impresión). |
| ModifyContent | `8` | Modificar el contenido del documento mediante operaciones distintas a las controladas por ModifyTextAnnotations, FillForm y 11. |
| ExtractContent | `10` | Controladores de seguridad de revisión 2) Copiar o extraer texto y gráficos del documento, incluida la extracción de texto y gráficos (en apoyo de la accesibilidad para usuarios con discapacidades o para otros fines). (Controladores de seguridad de revisión 3 o superior) Copiar o extraer texto y gráficos del documento mediante operaciones distintas a las controladas por ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Agregue o modifique anotaciones de texto, rellene campos de formulario interactivo y, si ModifyContent también está configurado, cree o modifique campos de formulario interactivo (incluidos los campos de firma). |
| FillForm | `100` | (controladores de seguridad de revisión 3 o superior) Complete los campos de formulario interactivo existentes (incluidos los campos de firma), incluso si ModifyTextAnnotations está claro. |
| ExtractContentWithDisabilities | `200` | (Manejadores de seguridad de revisión 3 o superior) Extrae texto y gráficos (en apoyo de la accesibilidad para usuarios con discapacidades o para otros fines). |
| AssembleDocument | `400` | (Controladores de seguridad de revisión 3 o superior) Ensamble el documento (inserte, gire o elimine páginas y cree marcadores o imágenes en miniatura), incluso si ModifyContent está claro. |
| PrintingQuality | `800` | (controladores de seguridad de revisión 3 o superior) Imprima el documento en una representación a partir de la cual se pueda generar una copia digital fiel del contenido del PDF. Cuando este bit está en blanco (y el bit 3 está establecido), la impresión se limita a una -representación de nivel de la apariencia, posiblemente de calidad degradada. |

### Ver también

* espacio de nombres [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
