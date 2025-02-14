---
title: ConvertToSpecifiedUnits
second_title: Riferimento API Aspose.SVG per .NET
description: Conserva lo stesso valore memorizzato sottostante ma reimposta lidentificatore di unità memorizzato su unitType specificato. Gli attributi delloggetto unitType valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. Ad esempio se il valore originale fosse 05 cm e il metodo fosse stato richiamato per la conversione in millimetri unitType verrebbe modificato in SVG_LENGTHTYPE_MM valueInSpecifiedUnits verrebbe modificato nel valore numerico 5 e valueAsString verrebbe modificato in 5 mm.
type: docs
weight: 50
url: /it/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Conserva lo stesso valore memorizzato sottostante, ma reimposta l'identificatore di unità memorizzato su unitType specificato. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. Ad esempio, se il valore originale fosse "0,5 cm" e il metodo fosse stato richiamato per la conversione in millimetri, unitType verrebbe modificato in SVG_LENGTHTYPE_MM, valueInSpecifiedUnits verrebbe modificato nel valore numerico 5 e valueAsString verrebbe modificato in "5 mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| unitType | UInt16 | Il tipo di unità a cui passare (ad esempio, SVG_LENGTHTYPE_MM). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | Codice [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err) Sollevato se unitType è SVG_LENGTHTYPE_UNKNOWN o non è una costante di tipo unità valida (una delle altre costanti SVG_LENGTHTYPE_* definite su questa interfaccia). |
| [DOMException](../../../aspose.svg.dom/domexception) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err) Aumentato quando la lunghezza corrisponde a un attributo di sola lettura o quando l'oggetto stesso è di sola lettura. |

### Guarda anche

* class [SVGLength](../../svglength)
* spazio dei nomi [Aspose.Svg.DataTypes](../../svglength)
* assemblea [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
