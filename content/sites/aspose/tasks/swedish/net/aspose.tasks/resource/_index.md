---
title: Resource
second_title: Aspose.Tasks för .NET API-referens
description: Representerar en resurs i ett projekt.
type: docs
weight: 1480
url: /sv/net/aspose.tasks/resource/
---
## Resource class

Representerar en resurs i ett projekt.

```csharp
public class Resource : IEquatable<Resource>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Assignments](../../aspose.tasks/resource/assignments) { get; } | Hämtar en samling resurstilldelningar för detta objekt. |
| [AvailabilityPeriods](../../aspose.tasks/resource/availabilityperiods) { get; } | Hämtar en instans av[`AvailabilityPeriodCollection`](../availabilityperiodcollection) class. Samlingen av perioder under vilka en resurs är tillgänglig. |
| [Baselines](../../aspose.tasks/resource/baselines) { get; } | Hämtar en BaselineCollection-instans för detta objekt. Baslinjevärdena för en resurs. |
| [ExtendedAttributes](../../aspose.tasks/resource/extendedattributes) { get; } | Hämtar värdena för ett utökat attribut. |
| virtual [IsRoot](../../aspose.tasks/resource/isroot) { get; } | Får flaggan som indikerar om resursen är en rotresurs. Rotresurs är en speciell resurs som är avsedd att stödja interna av MS Projects format och är inte avsedd att användas direkt från användarens kod. |
| [OutlineCode](../../aspose.tasks/resource/outlinecode) { get; } | Får ett OutlineCodeCollection-objekt. Värdet på en dispositionskod. |
| [ParentProject](../../aspose.tasks/resource/parentproject) { get; } | Hämtar överordnat projekt för den här behållaren. |
| [Rates](../../aspose.tasks/resource/rates) { get; } | Hämtar en instans av[`RateCollection`](../ratecollection) klass för detta objekt. Samlingen av perioder och kurser som är associerade med var och en. |
| [TimephasedData](../../aspose.tasks/resource/timephaseddata) { get; set; } | Hämtar eller ställer in en instans av[`TimephasedDataCollection`](../timephaseddatacollection) klass för detta objekt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Delete](../../aspose.tasks/resource/delete)() | Tar bort en resurs och dess tilldelningar från projektet. |
| override [Equals](../../aspose.tasks/resource/equals#equals_1)(object) | Returnerar ett värde som anger om denna instans är lika med ett angivet objekt. |
| [Equals](../../aspose.tasks/resource/equals#equals)(Resource) | Returnerar ett värde som anger om denna instans är lika med en specificerad instans av[`Resource`](../resource) class. |
| [Get&lt;T&gt;](../../aspose.tasks/resource/get)(Key&lt;T, RscKey&gt;) | Returnerar värdet som egenskapen är mappad till i den här behållaren. |
| override [GetHashCode](../../aspose.tasks/resource/gethashcode)() | Returnerar ett hashkodvärde för instansen av[`Resource`](../resource) class. |
| [GetTimephasedData](../../aspose.tasks/resource/gettimephaseddata#gettimephaseddata)(DateTime, DateTime) | Returnerar[`TimephasedDataCollection`](../timephaseddatacollection) för detta objekt med[`TimephasedData`](./timephaseddata) värden inom givna start- och slutdatum. |
| [GetTimephasedData](../../aspose.tasks/resource/gettimephaseddata#gettimephaseddata_1)(DateTime, DateTime, TimephasedDataType) | Returnerar en instans av[`TimephasedDataCollection`](../timephaseddatacollection) klass för detta objekt med[`TimephasedData`](./timephaseddata) värden inom givna start- och slutdatum för specificerade[`TimephasedDataType`](../timephaseddatatype) . |
| [Set](../../aspose.tasks/resource/set#set)(Key&lt;DateTime, RscKey&gt;, DateTime) | Mappar den angivna egenskapen till det angivna värdet i den här behållaren. |
| [Set&lt;T&gt;](../../aspose.tasks/resource/set#set_1)(Key&lt;T, RscKey&gt;, T) | Mappar den angivna egenskapen till det angivna värdet i den här behållaren. |
| override [ToString](../../aspose.tasks/resource/tostring)() | Returnerar kort strängrepresentation av instansen av[`Resource`](../resource) class. De exakta detaljerna i representationen är ospecificerade och kan komma att ändras. |

### Se även

* namnutrymme [Aspose.Tasks](../../aspose.tasks)
* hopsättning [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
