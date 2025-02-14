---
title: Transform
second_title: Aspose.GIS für .NET-API-Referenz
description: Gibt das Transformationsobjekt an das verwendet werden soll um Koordinaten zu quantisieren und Bögen in der Ausgabe TopoJSON zu deltakodieren.
type: docs
weight: 60
url: /de/net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

Gibt das Transformationsobjekt an, das verwendet werden soll, um Koordinaten zu quantisieren und Bögen in der Ausgabe TopoJSON zu deltakodieren.

```csharp
public TopoJsonTransform Transform { get; set; }
```

### Bemerkungen

Dies ist eine Schreiboption – sie wirkt sich nicht auf das Lesen aus. Diese Option schließt sich gegenseitig aus[`QuantizationNumber`](../quantizationnumber) - nur eine dieser beiden Optionen kann nicht sein`null` . Wenn dies nicht der Fall ist`null` - TopoJSON-Ausgabekoordinaten werden quantisiert und Bögen werden mit dem angegebenen -Transformationsobjekt deltacodiert. Weitere Einzelheiten zum Transformationsobjekt finden Sie in der TopoJSON-Spezifikation. Standardmäßig auf`null` .

### Siehe auch

* class [TopoJsonTransform](../../topojsontransform)
* class [TopoJsonOptions](../../topojsonoptions)
* namensraum [Aspose.Gis.Formats.TopoJson](../../topojsonoptions)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
