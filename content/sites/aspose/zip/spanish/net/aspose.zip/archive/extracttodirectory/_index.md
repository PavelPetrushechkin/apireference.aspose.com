---
title: ExtractToDirectory
second_title: Referencia de la API de Aspose.ZIP para .NET
description: Extrae todos los archivos del archivo en el directorio proporcionado.
type: docs
weight: 80
url: /es/net/aspose.zip/archive/extracttodirectory/
---
## Archive.ExtractToDirectory method

Extrae todos los archivos del archivo en el directorio proporcionado.

```csharp
public void ExtractToDirectory(string destinationDirectory)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| destinationDirectory | String | La ruta al directorio para colocar los archivos extraídos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *destinationDirectory* es nulo. |
| PathTooLongException | La ruta especificada, el nombre de archivo o ambos superan la longitud máxima definida por el sistema. Por ejemplo, en plataformas basadas en Windows, las rutas deben tener menos de 248 caracteres y los nombres de archivo deben tener menos de 260 caracteres. |
| SecurityException | La persona que llama no tiene el permiso necesario para acceder al directorio existente. |
| NotSupportedException | Si el directorio no existe, la ruta contiene un carácter de dos puntos (:) que no forma parte de la etiqueta de la unidad ("C:\"). |
| ArgumentException | *destinationDirectory* es una cadena de longitud cero, contiene solo espacios en blanco o contiene uno o más caracteres no válidos. Puede consultar caracteres no válidos mediante el método System.IO.Path.GetInvalidPathChars. -o- ruta tiene como prefijo, o contiene, solo un carácter de dos puntos (:). |
| IOException | El directorio especificado por ruta es un archivo. -o-- No se conoce el nombre de la red. |
| InvalidDataException | Se ha proporcionado una contraseña incorrecta. |

### Observaciones

Si el directorio no existe, se creará.

### Ejemplos

```csharp
using (var archive = new Archive("archive.zip")) 
{ 
   archive.ExtractToDirectory("C:\extracted");
}
```

### Ver también

* class [Archive](../../archive)
* espacio de nombres [Aspose.Zip](../../archive)
* asamblea [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
