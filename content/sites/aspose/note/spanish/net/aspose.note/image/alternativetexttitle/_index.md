---
title: AlternativeTextTitle
second_title: Aspose.Note para la referencia de la API de .NET
description: Obtiene o establece un título de texto alternativo para la imagen.
type: docs
weight: 40
url: /es/net/aspose.note/image/alternativetexttitle/
---
## Image.AlternativeTextTitle property

Obtiene o establece un título de texto alternativo para la imagen.

```csharp
public string AlternativeTextTitle { get; set; }
```

### Ejemplos

Muestra cómo configurar la descripción del texto para una imagen.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Images();

var document = new Document();
var page = new Page(document);
var image = new Image(document, dataDir + "image.jpg")
            {
                AlternativeTextTitle = "This is an image's title!",
                AlternativeTextDescription = "And this is an image's description!"
            };
page.AppendChildLast(image);
document.AppendChildLast(page);

dataDir = dataDir + "ImageAlternativeText_out.one";
document.Save(dataDir);
```

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Note](../../image)
* asamblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
