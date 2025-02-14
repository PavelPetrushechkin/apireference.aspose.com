---
title: OneSaveOptions
second_title: Aspose.Note para la referencia de la API de .NET
description: Permite especificar opciones adicionales al guardar documentos en formato OneNote.
type: docs
weight: 790
url: /es/net/aspose.note.saving/onesaveoptions/
---
## OneSaveOptions class

Permite especificar opciones adicionales al guardar documentos en formato OneNote.

```csharp
public sealed class OneSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OneSaveOptions](onesaveoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DocumentPassword](../../aspose.note.saving/onesaveoptions/documentpassword) { get; set; } | Obtiene o establece una contraseña para cifrar el contenido del documento. |
| [FontsSubsystem](../../aspose.note.saving/saveoptions/fontssubsystem) { get; set; } | Obtiene o establece la configuración de la fuente que se usará al guardar |
| [PageCount](../../aspose.note.saving/saveoptions/pagecount) { get; set; } | Obtiene o establece el número de páginas a guardar. Por defecto esMaxValue lo que significa que se procesarán todas las páginas del documento. |
| [PageIndex](../../aspose.note.saving/saveoptions/pageindex) { get; set; } | Obtiene o establece el índice de la primera página a guardar. Por defecto es 0. |
| [SaveFormat](../../aspose.note.saving/saveoptions/saveformat) { get; } | Obtiene el formato en el que se guarda el documento. |

### Ejemplos

Muestra cómo guardar un documento con cifrado.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_NoteBook();

Document document = new Document();
document.Save(dataDir + "CreatingPasswordProtectedDoc_out.one", new OneSaveOptions() { DocumentPassword = "pass" });
```

Muestra cómo guardar un documento usando OneSaveOptions.

```csharp
string inputFile = "Sample1.one";
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();
string outputFile = "SaveDocToOneNoteFormatUsingOneSaveOptions_out.one";

Document document = new Document(dataDir + inputFile);

document.Save(dataDir + outputFile, new OneSaveOptions());
```

### Ver también

* class [SaveOptions](../saveoptions)
* espacio de nombres [Aspose.Note.Saving](../../aspose.note.saving)
* asamblea [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
