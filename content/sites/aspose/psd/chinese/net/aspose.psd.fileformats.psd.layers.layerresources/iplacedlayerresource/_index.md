---
title: IPlacedLayerResource
second_title: Aspose.PSD for .NET API 参考
description: 定义 IPlacedLayerResource 接口该接口包含有关 PSD 文件中放置层的信息 是一个标记接口用于在 Adobe Photoshop 图像中指定 PlLdSold 和 Sole 资源 用于支持智能对象层Adobe Photoshop 图像
type: docs
weight: 2510
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/
---
## IPlacedLayerResource interface

定义 IPlacedLayerResource 接口，该接口包含有关 PSD 文件中放置层的信息。 是一个标记接口，用于在 Adobe® Photoshop® 图像中指定 PlLd、Sold 和 Sole 资源。 用于支持智能对象层Adobe® Photoshop® 图像。

```csharp
public interface IPlacedLayerResource
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/antialiaspolicy) { get; set; } | 获取或设置PSD图像中放置图层的抗锯齿策略。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/bottom) { get; set; } | 获取或设置放置图层在PSD图像中的底部位置。 |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/bounds) { get; set; } | 获取或设置PSD文件中放置层的边界。 |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/horizontalmeshpoints) { get; set; } | 获取或设置PSD文件中放置图层的水平网格点。 |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/horizontalmeshpointunit) { get; set; } | 获取或设置水平网格点的测量单位。 |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/iscustom) { get; set; } | 获取或设置一个值，该值指示此实例扭曲样式是否为自定义。 如果为 true，则包含网格点。如果设置为 false，它会删除网格点。 |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/items) { get; set; } | 获取或设置经线项目。 |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/left) { get; set; } | 获取或设置放置图层在PSD文件中的左侧位置。 |
| [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/pagenumber) { get; set; } | 获取或设置放置图层在PSD文件中的页码。 |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/perspective) { get; set; } | 获取或设置PSD文件中放置图层的透视值。 |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/perspectiveother) { get; set; } | 获取或设置PSD文件中放置图层的透视其他值。 |
| [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/placedlayertype) { get; set; } | 获取或设置PSD文件中放置图层的类型。 |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/right) { get; set; } | 获取或设置放置图层在PSD文件中的正确位置。 |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/top) { get; set; } | 获取或设置放置图层在 PSD 图像中的顶部位置。 |
| [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/totalpages) { get; set; } | 获取或设置PSD文件中放置图层的总页数。 |
| [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/transformmatrix) { get; set; } | 获取或设置PSD文件中放置图层的变换矩阵。 |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/uniqueid) { get; set; } | 获取或设置PSD图像中智能对象放置层的全局唯一标识符。 |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/uorder) { get; set; } | 获取或设置PSD文件中放置图层的U阶值 |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/value) { get; set; } | 获取或设置PSD图像中放置图层的warp值。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/version) { get; } | 获取PSD文件中放置图层的版本，一般为3-5. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/verticalmeshpoints) { get; set; } | 获取或设置PSD文件中放置图层的水平网格点。 |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/verticalmeshpointunit) { get; set; } | 获取或设置垂直网格点的测量单位。 |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/vorder) { get; set; } | 获取或设置PSD文件中放置图层的V阶值。 |

### 例子

以下代码演示了对 SoLdResource 资源的支持。

```csharp
[C#]

// 此示例显示如何获取或设置 PSD 文件的智能对象图层数据属性。

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                AssertAreEqual(expectedValue[2], resource.PageNumber);
                AssertAreEqual(expectedValue[3], resource.TotalPages);
                AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
                AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
                AssertAreEqual(8, resource.TransformMatrix.Length);
                AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
                AssertAreEqual(expectedValue[7], resource.Value);
                AssertAreEqual(expectedValue[8], resource.Perspective);
                AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
                AssertAreEqual(expectedValue[10], resource.Top);
                AssertAreEqual(expectedValue[11], resource.Left);
                AssertAreEqual(expectedValue[12], resource.Bottom);
                AssertAreEqual(expectedValue[13], resource.Right);
                AssertAreEqual(expectedValue[14], resource.UOrder);
                AssertAreEqual(expectedValue[15], resource.VOrder);

                AssertAreEqual(expectedValue[16], resource.Crop);
                AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
                AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
                AssertAreEqual(expectedValue[19], resource.DurationNumerator);
                AssertAreEqual(expectedValue[20], resource.DurationDenominator);
                AssertAreEqual(expectedValue[21], resource.FrameCount);
                AssertAreEqual(expectedValue[22], resource.Width);
                AssertAreEqual(expectedValue[23], resource.Height);
                AssertAreEqual(expectedValue[24], resource.Resolution);
                AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
                AssertAreEqual(expectedValue[26], resource.Comp);
                AssertAreEqual(expectedValue[27], resource.CompId);
                AssertAreEqual(expectedValue[28], resource.OriginalCompId);
                AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // 这个值也应该在 PlLdResource 中更改（使用指定的 UniqueId）
                // 其中一些必须与LinkDataSource中的下划线智能对象一致
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // 如果有的话，这个唯一的 Id 应该在引用中改变
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // 注意一些参数：Adobe® Photoshop® 可能无法读取图像
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // 不要改变这个，否则你将无法使用自由变换
                // 或将下划线智能对象更改为矢量类型
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // 应该有具有此唯一 ID 的有效 PlLdResource
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
