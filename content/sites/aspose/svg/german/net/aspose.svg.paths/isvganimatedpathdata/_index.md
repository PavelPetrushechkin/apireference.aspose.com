---
title: ISVGAnimatedPathData
second_title: Aspose.SVG für .NET-API-Referenz
description: Die SVGAnimatedPathDataSchnittstelle unterstützt Elemente mit einem dAttribut das SVGPfaddaten enthält und unterstützt die Fähigkeit dieses Attribut zu animieren.
type: docs
weight: 2450
url: /de/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Die SVGAnimatedPathData-Schnittstelle unterstützt Elemente mit einem „d“-Attribut, das SVG-Pfaddaten enthält, und unterstützt die Fähigkeit, dieses Attribut zu animieren.

```csharp
public interface ISVGAnimatedPathData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist) { get; } | Bietet Zugriff auf den aktuellen animierten Inhalt des 'd'-Attributs in einer Form, die eins zu eins mit der SVG-Syntax übereinstimmt. Wenn das angegebene Attribut oder die angegebene Eigenschaft animiert wird, enthält es den aktuellen animierten Wert des Attributs oder der Eigenschaft, und sowohl das Objekt selbst als auch sein Inhalt sind schreibgeschützt. Wenn das angegebene Attribut oder die Eigenschaft gerade nicht animiert wird, enthält es denselben Wert wie pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist) { get; } | Bietet Zugriff auf den Basisinhalt (dh statischen) des 'd'-Attributs in einer Form, die eins zu eins mit der SVG-Syntax übereinstimmt. Wenn also das 'd'-Attribut einen "absolute moveto (M)" und einen "absolute arcto (A)" Befehl hat, dann hat pathSegList zwei Einträge: einen SVG_PATHSEG_MOVETO_ABS und einen SVG_PATHSEG_ARC_ABS. |

### Siehe auch

* namensraum [Aspose.Svg.Paths](../../aspose.svg.paths)
* Montage [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
