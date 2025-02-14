---
title: FontName
second_title: Aspose.PSD for .NET API 参考
description: 获取或设置字体名称
type: docs
weight: 120
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontname/
---
## ITextStyle.FontName property

获取或设置字体名称。

```csharp
public string FontName { get; set; }
```

### 例子

以下代码演示了在部分样式中更改字体名称的能力。

```csharp
[C#]

string outputFilePng = "result_fontEditTest.png";
string outputFilePsd = "fontEditTest.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = new PsdImage(500, 500))
{
    FillLayer backgroundFillLayer = FillLayer.CreateInstance(FillType.Color);
    ((IColorFillSettings)backgroundFillLayer.FillSettings).Color = Color.White;
    image.AddLayer(backgroundFillLayer);

    TextLayer textLayer = image.AddTextLayer("Text 1", new Rectangle(10, 35, image.Width, 35));

    ITextPortion firstPortion = textLayer.TextData.Items[0];
    firstPortion.Style.FontSize = 24;
    firstPortion.Style.FontName = FontSettings.GetAdobeFontName("Comic Sans MS");

    var secondPortion = textLayer.TextData.ProducePortion();
    secondPortion.Text = "Text 2";
    secondPortion.Paragraph.Apply(firstPortion.Paragraph);
    secondPortion.Style.Apply(firstPortion.Style);
    secondPortion.Style.FontName = FontSettings.GetAdobeFontName("Arial");

    textLayer.TextData.AddPortion(secondPortion);
    textLayer.TextData.UpdateLayerData();

    image.Save(outputFilePng, new PngOptions());
    image.Save(outputFilePsd);
}

using (var image = (PsdImage)Image.Load(outputFilePsd))
{
    TextLayer textLayer = (TextLayer)image.Layers[2];

    string adobeFontName1 = FontSettings.GetAdobeFontName("Comic Sans MS");
    string adobeFontName2 = FontSettings.GetAdobeFontName("Arial");

    AssertAreEqual(adobeFontName1, textLayer.TextData.Items[0].Style.FontName);
    AssertAreEqual(adobeFontName2, textLayer.TextData.Items[1].Style.FontName);
}
```

### 也可以看看

* interface [ITextStyle](../../itextstyle)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
