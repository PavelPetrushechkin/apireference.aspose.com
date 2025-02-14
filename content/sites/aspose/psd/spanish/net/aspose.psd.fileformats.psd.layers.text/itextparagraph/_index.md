---
title: ITextParagraph
second_title: Referencia de API de Aspose.PSD para .NET
description: La interfaz para trabajar con el párrafo
type: docs
weight: 3460
url: /es/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

La interfaz para trabajar con el párrafo

```csharp
public interface ITextParagraph
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate) { get; set; } | Obtiene o establece un valor que indica si [guión automático]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading) { get; set; } | Obtiene o establece el interlineado automático. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari) { get; set; } | Obtiene o establece un valor que indica si este[`ITextParagraph`](../itextparagraph) es burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens) { get; set; } | Obtiene o establece los guiones consecutivos. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent) { get; set; } | Obtiene o establece la sangría final. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer) { get; set; } | Obtiene o establece un valor que indica si [every line composer]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent) { get; set; } | Obtiene o establece la sangría de la primera línea. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing) { get; set; } | Obtiene o establece el espaciado de glifos. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging) { get; set; } | Obtiene o establece un valor que indica si este[`ITextParagraph`](../itextparagraph) esta colgando. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize) { get; set; } | Obtiene o establece el tamaño de la palabra con guión. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification) { get; set; } | Obtiene o establece la justificación. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder) { get; set; } | Obtiene o establece el orden kinsoku. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype) { get; set; } | Obtiene o establece el tipo de interlineado. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing) { get; set; } | Obtiene o establece el espaciado entre letras. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen) { get; set; } | Obtiene o establece el guión de publicación. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen) { get; set; } | Obtiene o establece el guión previo. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter) { get; set; } | Obtiene o establece el espacio después de. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore) { get; set; } | Obtiene o establece el espacio anterior. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent) { get; set; } | Obtiene o establece la sangría inicial. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing) { get; set; } | Obtiene o establece el espaciado entre palabras. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone) { get; set; } | Obtiene o establece la zona. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply)(ITextParagraph) | Aplica el párrafo especificado. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal)(ITextParagraph) | Determina si el párrafo especificado es igual. |

### Ejemplos

El siguiente ejemplo demuestra que la alineación de texto a través de ITextPortion para idiomas de derecha a izquierda funciona correctamente.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

El siguiente ejemplo de código muestra la edición de porciones de texto y su estilo de texto.

```csharp
[C#]

const double Tolerance = 0.0001;
var filePath = "ThreeColorsParagraphs.psd";
var outputPath = "ThreeColorsParagraph_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var layer = im.Layers[i] as TextLayer;

        if (layer != null)
        {
            var portions = layer.TextData.Items;

            if (portions.Length != 4)
            {
                throw new Exception();
            }

            // Verificando el texto de cada porción
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Verificando los datos de los párrafos
            // Los párrafos tienen diferente justificación
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Todas las demás propiedades del primer y segundo párrafo son iguales
            for (int j = 0; j < portions.Length; j++)
            {
                var paragraph = portions[j].Paragraph;

                if (Math.Abs(paragraph.AutoLeading - 1.2) > Tolerance ||
                    paragraph.AutoHyphenate != false ||
                    paragraph.Burasagari != false ||
                    paragraph.ConsecutiveHyphens != 8 ||
                    Math.Abs(paragraph.StartIndent) > Tolerance ||
                    Math.Abs(paragraph.EndIndent) > Tolerance ||
                    paragraph.EveryLineComposer != false ||
                    Math.Abs(paragraph.FirstLineIndent) > Tolerance ||
                    paragraph.GlyphSpacing.Length != 3 ||
                    Math.Abs(paragraph.GlyphSpacing[0] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[1] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[2] - 1) > Tolerance ||
                    paragraph.Hanging != false ||
                    paragraph.HyphenatedWordSize != 6 ||
                    paragraph.KinsokuOrder != 0 ||
                    paragraph.LetterSpacing.Length != 3 ||
                    Math.Abs(paragraph.LetterSpacing[0]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[1]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[2]) > Tolerance ||
                    paragraph.LeadingType != LeadingMode.Auto ||
                    paragraph.PreHyphen != 2 ||
                    paragraph.PostHyphen != 2 ||
                    Math.Abs(paragraph.SpaceBefore) > Tolerance ||
                    Math.Abs(paragraph.SpaceAfter) > Tolerance ||
                    paragraph.WordSpacing.Length != 3 ||
                    Math.Abs(paragraph.WordSpacing[0] - 0.8) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[1] - 1.0) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[2] - 1.33) > Tolerance ||
                    Math.Abs(paragraph.Zone - 36.0) > Tolerance)
                {
                    throw new Exception();
                }
            }

            // Comprobando datos de estilo
            // Los estilos tienen diferentes colores y tamaños de letra
            if (Math.Abs(portions[0].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[1].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[2].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[3].Style.FontSize - 10) > Tolerance)
            {
                throw new Exception();
            }

            if (portions[0].Style.FillColor != Color.FromArgb(255, 145, 0, 0) ||
                portions[1].Style.FillColor != Color.FromArgb(255, 201, 128, 2) ||
                portions[2].Style.FillColor != Color.FromArgb(255, 18, 143, 4) ||
                portions[3].Style.FillColor != Color.FromArgb(255, 145, 42, 100))
            {
                throw new Exception();
            }

            for (int j = 0; j < portions.Length; j++)
            {
                var style = portions[j].Style;

                if (style.AutoLeading != true ||
                    style.HindiNumbers != false ||
                    style.Kerning != 0 ||
                    style.Leading != 0 ||
                    style.StrokeColor != Color.FromArgb(255, 175, 90, 163) ||
                    style.Tracking != 50)
                {
                    throw new Exception();
                }
            }

            // Ejemplo de edición de texto
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Ejemplo de eliminación de porciones de texto
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Ejemplo de cómo agregar una nueva porción de texto
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Ejemplo de edición de párrafo y estilo para porciones
            // Establecer justificación correcta
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Diferentes colores para cada estilo. Se cambiará, pero el renderizado no es totalmente compatible.
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Fuente diferente. Se cambiará, pero el renderizado no es totalmente compatible.
            portions[0].Style.FontSize = 6;
            portions[1].Style.FontSize = 8;
            portions[2].Style.FontSize = 10;

            layer.TextData.UpdateLayerData();

            im.Save(outputPath, new PsdOptions(im));

            break;
        }
    }
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
