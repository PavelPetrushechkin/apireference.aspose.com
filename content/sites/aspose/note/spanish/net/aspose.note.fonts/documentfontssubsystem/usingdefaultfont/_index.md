---
title: UsingDefaultFont
second_title: Aspose.Note para la referencia de la API de .NET
description: Crear una nueva instancia de DocumentFontsSubsystem utilizando el nombre de fuente predeterminado especificado.
type: docs
weight: 30
url: /es/net/aspose.note.fonts/documentfontssubsystem/usingdefaultfont/
---
## DocumentFontsSubsystem.UsingDefaultFont method

Crear una nueva instancia de DocumentFontsSubsystem utilizando el nombre de fuente predeterminado especificado.

```csharp
public static DocumentFontsSubsystem UsingDefaultFont(string defaultFontName, 
    Dictionary<string, string> fontsSubstitutions = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| defaultFontName | String | El nombre de fuente predeterminado. |
| fontsSubstitutions | Dictionary`2 | Las sustituciones de fuentes. |

### Valor_devuelto

El[`DocumentFontsSubsystem`](../../documentfontssubsystem) .

### Ejemplos

Muestra cómo guardar un documento en formato pdf utilizando la fuente predeterminada especificada.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(Path.Combine(dataDir, "missing-font.one"));

// Guarda el documento como PDF
dataDir = dataDir + "SaveUsingDocumentFontsSubsystemWithDefaultFontName_out.pdf";
oneFile.Save(dataDir, new PdfSaveOptions() 
                      {
                          FontsSubsystem = DocumentFontsSubsystem.UsingDefaultFont("Times New Roman")
                      });
```

### Ver también

* class [DocumentFontsSubsystem](../../documentfontssubsystem)
* espacio de nombres [Aspose.Note.Fonts](../../documentfontssubsystem)
* asamblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
