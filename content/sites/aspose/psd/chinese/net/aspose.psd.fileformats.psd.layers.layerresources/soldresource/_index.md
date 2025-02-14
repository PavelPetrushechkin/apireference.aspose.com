---
title: SoLdResource
second_title: Aspose.PSD for .NET API 参考
description: 定义包含有关 PSD 文件中智能对象层信息的 SoLdResource 类 用于支持 Adobe Photoshop 图像中的智能对象层
type: docs
weight: 2990
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

定义包含有关 PSD 文件中智能对象层信息的 SoLdResource 类。 用于支持 Adobe® Photoshop® 图像中的智能对象层。

```csharp
public class SoLdResource : SmartObjectResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SoLdResource](soldresource#constructor)() | 初始化[`SoLdResource`](../soldresource)class. 这个默认构造函数是为使用而设计的SoLdResourceLoader. 使用[`SmartResourceCreator`](../smartresourcecreator)用于创建 SoLdResource 类。 |
| [SoLdResource](soldresource#constructor_1)(Guid, bool, bool) | 初始化[`SoLdResource`](../soldresource) class. 需要设置 Items 属性或调用 InitializeItems() 以获取准备好的实例。 此构造函数是为使用而设计的[`SmartResourceCreator`](../smartresourcecreator) 并在单元测试中使用。 使用[`SmartResourceCreator`](../smartresourcecreator)用于创建 SoLdResource 类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy) { get; set; } | 获取或设置PSD图像中智能对象图层数据的抗锯齿策略。 |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom) { get; set; } | 获取或设置放置图层在PSD图像中的底部位置。 |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds) { get; set; } | 获取或设置PSD文件中放置层的边界。 |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp) { get; set; } | 获取或设置PSD文件中智能对象图层数据的comp值。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid) { get; set; } | 获取或设置子文档当前选择的组合的 ID，如果没有选择，则为 -1。 组合是设计人员可以创建的页面布局的组合。使用图层复合，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本 。图层组合是“图层”面板状态的快照。图层组合保存三种类型的图层选项但是 此属性获取PSD文件中智能对象图层的图层组合选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop) { get; set; } | 获取或设置PSD图像中智能对象图层数据的裁剪。 |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator) { get; set; } | 获取或设置时长分母。 |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator) { get; set; } | 获取或设置持续时间分子。 |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount) { get; set; } | 获取或设置PSD文件中智能对象图层数据的帧数。 |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator) { get; set; } | 获取或设置帧步长分母。 |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator) { get; set; } | 获取或设置帧步长分子。 |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height) { get; set; } | 获取或设置高度。 |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints) { get; set; } | 获取或设置PSD文件中放置图层的水平网格点。 |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit) { get; set; } | 获取或设置水平网格点的测量单位。 |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom) { get; set; } | 获取或设置一个值，该值指示此实例扭曲样式是否为自定义。 如果为 true，则包含网格点。如果设置为 false，它会删除网格点。 |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items) { get; set; } | 获取或设置PSD文件中智能对象图层数据的描述符项 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key) { get; } | 获取 SoLd 智能对象层资源密钥。 |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left) { get; set; } | 获取或设置放置图层在PSD文件中的左侧位置。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length) { get; } | 以字节为单位获取智能对象资源长度。 |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix) { get; set; } | 获取或设置PSD文件中智能对象图层数据的非仿射变换矩阵。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid) { get; } | 获取子文档当前选择的 Comp 的原始 ID，如果没有选择，则为 -1。 此属性获取 PSD 文件中智能对象层的原始层 Comp 选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber) { get; set; } | 获取或设置PSD文件中智能对象图层数据的页码。 |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective) { get; set; } | 获取或设置PSD文件中放置图层的透视值。 |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother) { get; set; } | 获取或设置PSD文件中放置图层的透视其他值。 |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid) { get; set; } | 获取或设置此智能对象图层数据在 PSD 图像中的唯一标识符。 |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype) { get; set; } | 获取或设置PSD文件中智能对象图层数据的类型。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion) { get; } | 获取智能对象资源所需的最低 psd 版本。 0 表示没有限制。 |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution) { get; set; } | 获取或设置PSD文件中智能对象图层数据的分辨率。 |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit) { get; set; } | 获取或设置PSD文件中智能对象图层数据的分辨率度量单位。 |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right) { get; set; } | 获取或设置放置图层在PSD文件中的正确位置。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature) { get; } | 获取智能对象资源签名。 |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top) { get; set; } | 获取或设置放置图层在 PSD 图像中的顶部位置。 |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages) { get; set; } | 获取或设置PSD文件中智能对象图层数据的总页数。 |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix) { get; set; } | 获取或设置PSD文件中智能对象图层数据的变换矩阵。 |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid) { get; set; } | 获取或设置智能对象图层数据的全局唯一标识[`SmartObjectResource`](../smartobjectresource)在 PSD 图像中。 |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder) { get; set; } | 获取或设置PSD文件中放置图层的U阶值 |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value) { get; set; } | 获取或设置PSD图像中放置图层的warp值。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version) { get; } | 获取PSD文件中放置图层的版本，一般为3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints) { get; set; } | 获取或设置PSD文件中放置图层的水平网格点。 |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit) { get; set; } | 获取或设置垂直网格点的测量单位。 |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder) { get; set; } | 获取或设置PSD文件中放置图层的V阶值。 |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width) { get; set; } | 获取或设置宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save)(StreamContainer, int) | 将智能对象资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | 返回一个String代表这个实例。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey) | 类型工具信息键：'SoLd'. |

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

* class [SmartObjectResource](../smartobjectresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
