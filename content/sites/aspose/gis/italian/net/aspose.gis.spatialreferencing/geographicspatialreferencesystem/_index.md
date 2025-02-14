---
title: GeographicSpatialReferenceSystem
second_title: Riferimento API Aspose.GIS per .NET
description: Un SRS geografico è un SRS basato su longitudine e latitudine. Un SRS geografico può essere bidimensionale o tridimensionale. Se SRS geografico è tridimensionale allora è in realtà un SRS composto di SRS bidimensionale e SRS verticale.
type: docs
weight: 2030
url: /it/net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---
## GeographicSpatialReferenceSystem class

Un SRS geografico è un SRS basato su longitudine e latitudine. Un SRS geografico può essere bidimensionale o tridimensionale. Se SRS geografico è tridimensionale, allora è in realtà un SRS composto di SRS bidimensionale e SRS verticale.

```csharp
public abstract class GeographicSpatialReferenceSystem : SpatialReferenceSystem
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [AngularUnit](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/angularunit) { get; } | Unità, utilizzata per le dimensioni angolari, in questo SRS. |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound) { get; } | Restituisce questo SRS convertito in[`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem) . Usa[`IsCompound`](../spatialreferencesystem/iscompound) per scoprire se la conversione è possibile. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric) { get; } | Restituisce questo SRS convertito in[`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem) . Usa[`Type`](../spatialreferencesystem/type) per scoprire se la conversione è possibile. |
| [AsGeographic](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/asgeographic) { get; } | Restituisce questo. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal) { get; } | Restituisce questo SRS convertito in[`LocalSpatialReferenceSystem`](../localspatialreferencesystem) . Usa[`Type`](../spatialreferencesystem/type) per scoprire se la conversione è possibile. |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected) { get; } | Restituisce questo SRS convertito in[`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem) . Usa[`Type`](../spatialreferencesystem/type) per scoprire se la conversione è possibile. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical) { get; } | Restituisce questo SRS convertito in[`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem) . Usa[`Type`](../spatialreferencesystem/type) per scoprire se la conversione è possibile. |
| abstract [AxisesOrder](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/axisesorder) { get; } | Ordine degli assi in questo SRS. Se questo SRS non è valido e ha direzioni degli assi errate,Invalid viene restituito. |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/dimensionscount) { get; } | Restituisce il conteggio delle dimensioni in questo SRS. Per l'SRS geografico questo può essere: due - se si tratta di un SRS geografico singolo. tre - se si tratta di un SRS composto, che consiste in un SRS singolo, bidimensionale, geografico e SRS verticale, che aggiunge la terza dimensione. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode) { get; } | Se questo identificatore di oggetti è identificatore EPSG, restituisci il suo codice. Altrimenti - restituisce -1. |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum) { get; } | Restituisce il dato geografico di questo SRS. |
| [HasGeographicDatum](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/hasgeographicdatum) { get; } | Restituisce`true` , poiché gli SRS geografici hanno sempre il primo meridiano. |
| [HasPrimeMeridian](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/hasprimemeridian) { get; } | Restituisce`true` , poiché gli SRS geografici hanno sempre il primo meridiano. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier) { get; } | Identificatore di questo oggetto identificabile. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound) { get; } | Restituisce se questo SRS è composto (unione di due SRS). Sono considerate valide le seguenti combinazioni di SRS in SRS composto: SRS geografico + SRS verticale, in questo caso il tipo di SRS composto saràGeographic . SRS proiettato + SRS verticale, in questo caso il tipo di SRS composto saràProjected . Se la combinazione di SRS è diversa, sarà il tipo di SRS compostoUnknown . |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle) { get; } | Restituisce se questo SRS è singolo (non un'unione di due SRS). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid) { get; } | Come[`Validate`](../spatialreferencesystem/validate) , ma non restituisce il messaggio di errore. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name) { get; } | Nome di questo oggetto. |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian) { get; } | Restituisce il primo meridiano di questo SRS. |
| [Type](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/type) { get; } | RestituisceGeographic . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto)(SpatialReferenceSystem) | Crea la trasformazione da questo`Sistema di riferimento spaziale` ad un altro`Sistema di riferimento spaziale` . |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt)() | Restituisce la rappresentazione di questo SRS come stringa WKT. La stringa WKT risultante corrisponderà alla specifica OGC 01-009, solitamente denominata "WKT1". |
| abstract [GetAxis](../../aspose.gis.spatialreferencing/spatialreferencesystem/getaxis)(int) | Ottieni[`Axis`](../axis) che descrive la dimensione. |
| abstract [GetUnit](../../aspose.gis.spatialreferencing/spatialreferencesystem/getunit)(int) | Ottieni[`Unit`](../unit)di dimensione. |
| virtual [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent)(SpatialReferenceSystem) | Rileva se questo SRS è equivalente ad altri SRS. . |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | Crea la trasformazione da questo`Sistema di riferimento spaziale` ad un altro`Sistema di riferimento spaziale` . |
| abstract [Validate](../../aspose.gis.spatialreferencing/spatialreferencesystem/validate)(out string) | Determina se questo SRS è valido. |

### Guarda anche

* class [SpatialReferenceSystem](../spatialreferencesystem)
* spazio dei nomi [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* assemblea [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
