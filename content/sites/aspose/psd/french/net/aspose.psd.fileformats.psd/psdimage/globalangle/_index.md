---
title: GlobalAngle
second_title: Référence de l'API Aspose.PSD pour .NET
description: Obtient ou définit langle global.
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Obtient ou définit l'angle global.

```csharp
public int GlobalAngle { get; set; }
```

### Exemples

Le code suivant illustre la prise en charge de la propriété PsdImage.GlobalAngle pour modifier la valeur d'angle global.

```csharp
[C#]

// Lorsque la propriété DropShadowEffect.UseGlobalLight est 'true', alors l'objet DropShadowEffect utilise la valeur d'angle de la propriété PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Voir également

* class [PsdImage](../../psdimage)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
