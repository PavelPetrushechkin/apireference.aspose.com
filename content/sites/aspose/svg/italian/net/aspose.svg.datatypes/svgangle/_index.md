---
title: SVGAngle
second_title: Riferimento API Aspose.SVG per .NET
description: Linterfaccia SVGAngle corrisponde al tipo di dati di base dellangolo.
type: docs
weight: 80
url: /it/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

L'interfaccia SVGAngle corrisponde al tipo di dati di base dell'angolo.

```csharp
public class SVGAngle : SVGValueType
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype) { get; } | Il tipo del valore come specificato da una delle costanti SVG_ANGLETYPE_* definite su questa interfaccia. |
| [Value](../../aspose.svg.datatypes/svgangle/value) { get; set; } | Il valore dell'angolo come valore in virgola mobile, in gradi. L'impostazione di questo attributo farà sì che valueInSpecifiedUnits e valueAsString vengano aggiornati automaticamente per riflettere questa impostazione. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring) { get; set; } | Il valore dell'angolo come valore stringa, nelle unità espresse da unitType. L'impostazione di questo attributo farà sì che value, valueInSpecifiedUnits e unitType vengano aggiornati automaticamente per riflettere questa impostazione. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits) { get; set; } | Il valore dell'angolo come valore in virgola mobile, nelle unità espresse da unitType. L'impostazione di questo attributo farà sì che value e valueAsString vengano aggiornati automaticamente per riflettere questa impostazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits)(ushort) | Conserva lo stesso valore memorizzato sottostante, ma reimposta l'identificatore di unità memorizzato su unitType specificato. Gli attributi dell'oggetto unitType, valueInSpecifiedUnits e valueAsString potrebbero essere modificati come risultato di questo metodo. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose)() | Rilascia risorse non gestite e, facoltativamente, gestite. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits)(ushort, float) | Reimposta il valore come numero con un unitType associato, sostituendo così i valori per tutti gli attributi sull'oggetto. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg) | Il tipo di unità è stato impostato in modo esplicito su gradi. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad) | Il tipo di unità è radianti. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad) | Il tipo di unità è radianti. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown) | Il tipo di unità non è uno dei tipi di unità predefiniti. Non è valido tentare di definire un nuovo valore di questo tipo o tentare di cambiare un valore esistente in questo tipo. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified) | Non è stato fornito alcun tipo di unità (ovvero, è stato specificato un valore senza unità). Per gli angoli, un valore senza unità viene trattato come se fossero specificati i gradi. |

### Guarda anche

* class [SVGValueType](../svgvaluetype)
* spazio dei nomi [Aspose.Svg.DataTypes](../../aspose.svg.datatypes)
* assemblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
