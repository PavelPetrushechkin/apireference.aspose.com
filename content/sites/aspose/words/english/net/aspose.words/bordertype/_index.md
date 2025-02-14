---
title: BorderType
second_title: Aspose.Words for .NET API Reference
description: Specifies sides of a border.
type: docs
weight: 90
url: /net/aspose.words/bordertype/
---
## BorderType enumeration

Specifies sides of a border.

```csharp
public enum BorderType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `-1` | Default value. |
| Bottom | `0` | Specifies the bottom border of a paragraph or a table cell. |
| Left | `1` | Specifies the left border of a paragraph or a table cell. |
| Right | `2` | Specifies the right border of a paragraph or a table cell. |
| Top | `3` | Specifies the top border of a paragraph or a table cell. |
| Horizontal | `4` | Specifies the horizontal border between cells in a table or between conforming paragraphs. |
| Vertical | `5` | Specifies the vertical border between cells in a table. |
| DiagonalDown | `6` | Specifies the diagonal border in a table cell. |
| DiagonalUp | `7` | Specifies the diagonal border in a table cell. |

## Examples

Shows how to insert a paragraph with a top border.

```csharp
Document doc = new Document();
DocumentBuilder builder = new DocumentBuilder(doc);

Border topBorder = builder.ParagraphFormat.Borders[BorderType.Top];
topBorder.Color = Color.Red;
topBorder.LineWidth = 4.0d;
topBorder.LineStyle = LineStyle.DashSmallGap;

builder.Writeln("Text with a red top border.");

doc.Save(ArtifactsDir + "Border.ParagraphTopBorder.docx");
```

### See Also

* namespace [Aspose.Words](../../aspose.words)
* assembly [Aspose.Words](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
