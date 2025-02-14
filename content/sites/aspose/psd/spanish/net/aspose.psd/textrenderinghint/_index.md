---
title: TextRenderingHint
second_title: Referencia de API de Aspose.PSD para .NET
description: Especifica la calidad de la representación del texto.
type: docs
weight: 5630
url: /es/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

Especifica la calidad de la representación del texto.

```csharp
public enum TextRenderingHint
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SystemDefault | `0` | Cada carácter se dibuja utilizando su mapa de bits de glifo, con la sugerencia de representación predeterminada del sistema. El texto se dibujará utilizando cualquier configuración de suavizado de fuentes que el usuario haya seleccionado para el sistema. |
| SingleBitPerPixelGridFit | `1` | Cada carácter se dibuja utilizando su mapa de bits de glifo. Las sugerencias se utilizan para mejorar la apariencia del personaje en los tallos y la curvatura. |
| SingleBitPerPixel | `2` | Cada carácter se dibuja utilizando su mapa de bits de glifo. No se utilizan sugerencias. |
| AntiAliasGridFit | `3` | Cada carácter se dibuja utilizando su mapa de bits de glifo suavizado con sugerencias. Mucha mejor calidad debido al antialiasing, pero a un mayor costo de rendimiento. |
| AntiAlias | `4` | Cada carácter se dibuja utilizando su mapa de bits de glifo suavizado sin sugerencias. Mejor calidad debido al antialiasing. Las diferencias en el ancho de la plica pueden notarse porque las sugerencias están desactivadas. |
| ClearTypeGridFit | `5` | Cada carácter se dibuja utilizando su mapa de bits ClearType de glifo con sugerencias. El ajuste de la más alta calidad. Se utiliza para aprovechar las características de la fuente ClearType. |

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
