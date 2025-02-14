---
title: License
second_title: Riferimento API Aspose.SVG per .NET
description: Fornisce i metodi per concedere in licenza il componente.
type: docs
weight: 2160
url: /it/net/aspose.svg/license/
---
## License class

Fornisce i metodi per concedere in licenza il componente.

```csharp
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense)(Stream) | concede in licenza il componente. |
| [SetLicense](../../aspose.svg/license/setlicense#setlicense_1)(string) | concede in licenza il componente. |

### Esempi

In questo esempio, verrà effettuato un tentativo di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene  il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e quindi nelle risorse incorporate dell'assembly chiamante.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

il file jar del componente:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Guarda anche

* spazio dei nomi [Aspose.Svg](../../aspose.svg)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
