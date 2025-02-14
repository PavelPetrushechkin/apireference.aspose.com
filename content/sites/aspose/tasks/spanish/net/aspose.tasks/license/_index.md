---
title: License
second_title: Referencia de Aspose.Tasks para la API de .NET
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 850
url: /es/net/aspose.tasks/license/
---
## License class

Proporciona métodos para licenciar el componente.

```csharp
public class License
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license)() | Inicializa una nueva instancia del[`License`](../license) clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLicense](../../aspose.tasks/license/setlicense#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.tasks/license/setlicense#setlicense_1)(string) | Licencia el componente. |

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene  el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

el archivo jar del componente:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ver también

* espacio de nombres [Aspose.Tasks](../../aspose.tasks)
* asamblea [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
