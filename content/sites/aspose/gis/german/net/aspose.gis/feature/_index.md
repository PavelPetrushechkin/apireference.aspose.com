---
title: Feature
second_title: Aspose.GIS für .NET-API-Referenz
description: Ein geografisches Merkmal das aus einer Geometrie und benutzerdefinierten Attributen besteht.
type: docs
weight: 120
url: /de/net/aspose.gis/feature/
---
## Feature class

Ein geografisches Merkmal, das aus einer Geometrie und benutzerdefinierten Attributen besteht.

```csharp
public class Feature
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Geometry](../../aspose.gis/feature/geometry) { get; set; } | Ruft die Geometrie des Features ab oder legt sie fest. Kann nicht sein`null` , verwenden[`Null`](../../aspose.gis.geometries/geometry/null) um fehlende Geometrie anzuzeigen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CopyValues](../../aspose.gis/feature/copyvalues)(Feature) | Kopiert Werte von Attributen aus einem anderen Feature. |
| [GetValue](../../aspose.gis/feature/getvalue#getvalue)(string) | Ruft den Wert eines Attributs ab. |
| [GetValue&lt;T&gt;](../../aspose.gis/feature/getvalue#getvalue_1)(string) | Ruft den Wert eines Attributs ab. |
| [GetValueOrDefault](../../aspose.gis/feature/getvalueordefault#getvalueordefault)(string, object) | Ruft den Wert eines Attributs ab, oder[`DefaultValue`](../featureattribute/defaultvalue) wenn der Wert nicht gesetzt ist oder`Null` . |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault#getvalueordefault_1)(string) | Ruft den Wert eines Attributs ab, oder[`DefaultValue`](../featureattribute/defaultvalue) wenn der Wert nicht gesetzt ist oder`Null` . |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault#getvalueordefault_2)(string, object) | Ruft den Wert eines Attributs ab, oder[`DefaultValue`](../featureattribute/defaultvalue) wenn der Wert nicht gesetzt ist oder`Null` . |
| [GetValues](../../aspose.gis/feature/getvalues)(object[], object) | Gibt die Werte für alle Attribute in einem Array zurück. |
| [GetValuesDump](../../aspose.gis/feature/getvaluesdump)(object) | Gibt die Werte für alle Attribute in einem Array zurück. Ziehen Sie die Verwendung in Betracht[`GetValues`](./getvalues)Methode, um zusätzliche Speicherzuweisung zu vermeiden. |
| [GetValuesList&lt;T&gt;](../../aspose.gis/feature/getvalueslist)(string, string) | Ruft die Werte einer Attributsequenz als Liste ab. |
| [IsValueNull](../../aspose.gis/feature/isvaluenull)(string) | Bestimmt, ob das angegebene Attribut explizit auf gesetzt wurde`Null` wert. |
| [IsValueSet](../../aspose.gis/feature/isvalueset)(string) | Überprüft, ob der Attributwert in dieser Funktion festgelegt ist. |
| [SetValue&lt;T&gt;](../../aspose.gis/feature/setvalue)(string, T) | Legt einen neuen Wert eines Attributs fest. |
| [SetValueNull](../../aspose.gis/feature/setvaluenull)(string) | Setzt den Wert des Attributs auf`Null` . |
| [SetValues](../../aspose.gis/feature/setvalues)(object[]) | Legt neue Werte für alle Attribute fest. Ziehen Sie auch die Verwendung in Betracht[`CopyValues`](./copyvalues) Methode zum Optimieren von Einstellungswerten in einem Aufruf. |
| [UnsetValue](../../aspose.gis/feature/unsetvalue)(string) | Entfernt den Attributwert von dieser Funktion. |

### Siehe auch

* namensraum [Aspose.Gis](../../aspose.gis)
* Montage [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
