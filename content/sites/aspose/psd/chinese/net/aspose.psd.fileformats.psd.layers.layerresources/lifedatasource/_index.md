---
title: LiFeDataSource
second_title: Aspose.PSD for .NET API 参考
description: 定义包含有关外部链接文件的信息的 LnkeDataSource 类 这是有助于修改 Adobe Photoshop 文件的 PSD 文件格式操作 API 的一部分
type: docs
weight: 2660
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---
## LiFeDataSource class

定义包含有关外部链接文件的信息的 LnkeDataSource 类。 这是有助于修改 Adobe® Photoshop® 文件的 PSD 文件格式操作 API 的一部分

```csharp
public class LiFeDataSource : LinkDataSource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LiFeDataSource](lifedatasource#constructor)() | 初始化[`LiFeDataSource`](../lifedatasource)类. |
| [LiFeDataSource](lifedatasource#constructor_1)(int, Guid, string, string, string) | 初始化[`LiFeDataSource`](../lifedatasource)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AdobeStockId](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestockid) { get; set; } | 获取或设置图形库 AdobeStockId，用于 Adobe® Photoshop® CC Libraries。 |
| [AdobeStockLicenseState](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestocklicensestate) { get; } | 获取用于 Adobe® Photoshop® CC 库的 adobe stock 许可证的状态（如果可用）。 |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate) { get; set; } | 获取或设置一个值，指示 PSD 资源是否被锁定。 资源锁定状态，用于 Adobe® Photoshop® СС 库资源。 |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime) { get; set; } | 获取或设置资产修改时间，用于 Adobe® Photoshop® СС 库资产。 |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid) { get; set; } | 获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源的 liFE 或 liFD 数据源中的子文档标识符。 |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid) { get; set; } | 获取或设置子文档当前选择的组合的 ID，如果没有选择，则为 -1。 组合是设计人员可以创建的页面布局的组合。使用图层复合，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本 。图层组合是“图层”面板状态的快照。图层组合保存三种类型的图层选项但 此属性获取智能对象的图层组合选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Date](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/date) { get; set; } | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的最后写入日期和时间。 |
| [ElementName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementname) { get; set; } | 获取或设置图形库元素名称，用于 Adobe® Photoshop® CC Libraries。 |
| [ElementRef](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementref) { get; set; } | 获取或设置图形库元素参考，用于 Adobe® Photoshop® CC Libraries。 |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator) { get; set; } | 获取或设置PSD格式LnkE/Lnk2资源的文件创建者 |
| [FileName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filename) { get; set; } | 获取或设置 PSD 链接资源中的外部或嵌入文件的名称。 |
| [FileSize](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filesize) { get; set; } | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的大小。 |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype) { get; set; } | 获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源包含或链接的嵌入或外部文件的类型。 |
| [FullPath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath) { get; set; } | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的完整路径。 |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor) { get; set; } | 获取或设置一个值，该值指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。 |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) { get; } | 获取一个值，该值指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® СС 库项目。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length) { get; } | 获取链接数据源长度（以字节为单位）。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid) { get; } | 获取子文档当前选择的 Comp 的原始 ID，如果没有选择，则为 -1。 此属性获取智能对象的原始层 Comp 选择标识符。 [智能对象中的图层组合](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename) { get; } | 获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。 |
| [RelativePath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath) { get; set; } | 获取或设置外部文件在 PSD LnkE 资源的 LiFE 数据源中的相对路径。 |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type) { get; } | 获取 Adobe® Photoshop® 全局链接数据源类型，可以是以下之一或无： 与 PSD Lnk2Resource 对应的嵌入链接文件 liFD_ 与 PSD LnkeResource 对应的外部链接文件 liFE_ 链接文件别名 liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid) { get; } | 获取PSD链接资源中数据源的全局唯一标识。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version) { get; } | 获取PSD LnkE/Lnk2资源中数据源的版本。 |

### 例子

此示例演示如何获取和设置 Psd LnkE 资源的属性。

```csharp
[C#]

string message = "The example works incorrectly.";
void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(message);
    }
}

// 此示例演示如何获取和设置包含有关外部链接文件的信息的 Psd LnkE 资源的属性。
void ExampleOfLnkEResourceSupport(
    string fileName,
    int length,
    int length2,
    int length3,
    int length4,
    string fullPath,
    string date,
    double assetModTime,
    string childDocId,
    bool locked,
    string uid,
    string name,
    string originalFileName,
    string fileType,
    long size,
    int version)
{
    string outputPath = fileName;
    using (PsdImage image = (PsdImage)Image.Load(fileName))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                LiFeDataSource lifeSource = lnkeResource[0];
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lifeSource.UniqueId, new Guid(uid));
                AssertAreEqual(lifeSource.FullPath, fullPath);
                AssertAreEqual(lifeSource.Date.ToString(CultureInfo.InvariantCulture), date);
                AssertAreEqual(lifeSource.AssetModTime, assetModTime);
                AssertAreEqual(lifeSource.FileName, name);
                AssertAreEqual(lifeSource.FileSize, size);
                AssertAreEqual(lifeSource.ChildDocId, childDocId);
                AssertAreEqual(lifeSource.Version, version);
                AssertAreEqual(lifeSource.FileType.TrimEnd(' '), fileType);
                AssertAreEqual(lifeSource.FileCreator.TrimEnd(' '), string.Empty);
                AssertAreEqual(lifeSource.OriginalFileName, originalFileName);
                AssertAreEqual(false, lnkeResource.IsEmpty);
                AssertAreEqual(true, lifeSource.Type == LinkDataSourceType.liFE);
                if (version == 7)
                {
                    AssertAreEqual(lifeSource.AssetLockedState, locked);
                }

                if (lifeSource.HasFileOpenDescriptor)
                {
                    AssertAreEqual(lifeSource.CompId, -1);
                    AssertAreEqual(lifeSource.OriginalCompId, -1);
                }

                lifeSource.FullPath =
                    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                AssertAreEqual(lnkeResource.Length, length2);
                lifeSource.FileName = "rgb8_2x23.png";
                AssertAreEqual(lnkeResource.Length, length3);
                lifeSource.ChildDocId = Guid.NewGuid().ToString();
                AssertAreEqual(lnkeResource.Length, length4);
                lifeSource.Date = DateTime.Now;
                lifeSource.AssetModTime = double.MaxValue;
                lifeSource.FileSize = long.MaxValue;
                lifeSource.FileType = "test";
                lifeSource.FileCreator = "file";
                lifeSource.CompId = int.MaxValue;
                break;
            }
        }

        AssertAreEqual(true, lnkeResource != null);

        image.Save(outputPath, new PsdOptions(image));
    }
}

// 此示例演示如何获取和设置包含有关外部链接的 JPEG 文件信息的 Psd LnkeResource 的属性。
ExampleOfLnkEResourceSupport(
    @"photooverlay_5_new.psd",
    0x21c,
    0x26c,
    0x274,
    0x27c,
    @"file:///C:/Users/cvallejo/Desktop/photo.jpg",
    "05/09/2017 22:24:51",
    0,
    "F062B9DB73E8D124167A4186E54664B0",
    false,
    "02df245c-36a2-11e7-a9d8-fdb2b61f07a7",
    "photo.jpg",
    "photo.jpg",
    "JPEG",
    0x1520d,
    7);

// 此示例演示如何获取和设置包含有关外部链接 PNG 文件信息的 PSD LnkeResource 的属性。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked.psd",
    0x284,
    0x290,
    0x294,
    0x2dc,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Issues/PSDNET-491/rgb8_2x2.png",
    "04/14/2020 14:23:44",
    0,
    string.Empty,
    false,
    "5867318f-3174-9f41-abca-22f56a75247e",
    "rgb8_2x2.png",
    "rgb8_2x2.png",
    "png",
    0x53,
    7);

// 此示例演示如何获取和设置 PSD LnkeResource 的属性，该资源包含有关两个外部链接的 PNG 和 PSD 文件的信息。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked2.psd",
    0x590,
    0x580,
    0x554,
    0x528,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/AddColorBalanceAdjustmentLayer.psd",
    "01/15/2020 13:02:00",
    0,
    "adobe:docid:photoshop:9312f484-3403-a644-8973-e725abc95fb7",
    false,
    "78a5b588-364f-0940-a2e5-a450a031aa48",
    "AddColorBalanceAdjustmentLayer.psd",
    "AddColorBalanceAdjustmentLayer.psd",
    "8BPS",
    0x4aea,
    7);

// 此示例演示如何获取和设置 Photoshop Psd LnkeResource 的属性，该资源包含有关外部链接 CC 库资源的信息。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_asset_linked.psd",
    0x398,
    0x38c,
    0x388,
    0x3d0,
    @"CC Libraries Asset “rgb8_2x2_linked/rgb8_2x2” (Feature is available in Photoshop CC 2015)",
    "01/01/0001 00:00:00",
    1588890915488.0d,
    string.Empty,
    false,
    "ec15f0a8-7f13-a640-b928-7d29c6e9859c",
    "rgb8_2x2_linked",
    "rgb8_2x2.png",
    "png",
    0,
    7);
```

下面的代码演示了对 LnkeResource 资源的支持。

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] ComplexLnkEResourceSupportCases = new object[]
{
    new object[]
    {
        "10fc87d0-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/or hdr btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633541.0d,
        "uuid:8485ca8d-9496-7f4d-9ef7-4243a00d4161",
        "OneReview-InDesign-InContextTranslation",
        "or hdr btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cc-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs Id icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633512.0d,
        "uuid:c18be832-adf7-4b43-8223-a9740807a66c",
        "OneReview-InDesign-InContextTranslation",
        "cs Id icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fef79c-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/pointer cursor” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633570.0d,
        "uuid:9d7ccaac-f094-214b-8721-1a07ae8700a9",
        "OneReview-InDesign-InContextTranslation",
        "pointer cursor.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x03c0
    },
    new object[]
    {
        "10fef79a-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/x” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633555.0d,
        "uuid:b28aa699-21d6-2d4d-a4c7-790234c1b6ba",
        "OneReview-InDesign-InContextTranslation",
        "x.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x38c
    },
    new object[]
    {
        "10fef79b-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/modal btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633562.0d,
        "uuid:1bd42767-058d-da44-bdee-eada3b9d40a5",
        "OneReview-InDesign-InContextTranslation",
        "modal btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87cd-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs ppt icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633519.0d,
        "uuid:215499ac-ac44-b44d-894b-9ff2c7008d9d",
        "OneReview-InDesign-InContextTranslation",
        "cs ppt icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cf-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs AI icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633534.0d,
        "uuid:a67964d4-8682-d649-8118-474cb1776264",
        "OneReview-InDesign-InContextTranslation",
        "cs AI icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87ce-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs PSD icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633527.0d,
        "uuid:8e9d5745-9f23-6f49-968e-647a45811bcb",
        "OneReview-InDesign-InContextTranslation",
        "cs PSD icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
};

void ExampleOfComplexLnkEResourceSupport(string filePath, int length, int length2, object[] dataSourceExpectedValues)
{
    filePath = "PSDNET652_1" + Path.DirectorySeparatorChar + filePath;
    string fileName = Path.GetFileName(filePath);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                AssertAreEqual(lnkeResource.DataSourceCount, 8);
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lnkeResource.IsEmpty, false);

                for (int i = 0; i < lnkeResource.DataSourceCount; i++)
                {
                    LiFeDataSource liFeSource = lnkeResource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(liFeSource.Type, LinkDataSourceType.liFE);
                    AssertAreEqual(liFeSource.UniqueId, new Guid((string)expected[0]));
                    AssertAreEqual(liFeSource.FullPath, expected[1]);
                    AssertAreEqual(liFeSource.Date.ToString(CultureInfo.InvariantCulture), expected[2]);
                    AssertAreEqual(liFeSource.AssetModTime, expected[3]);
                    AssertAreEqual(liFeSource.ChildDocId, expected[4]);
                    AssertAreEqual(liFeSource.FileName, expected[5]);
                    AssertAreEqual(liFeSource.OriginalFileName, expected[6]);
                    AssertAreEqual(liFeSource.FileSize, expected[7]);
                    AssertAreEqual(liFeSource.FileType, expected[8]);
                    AssertAreEqual(liFeSource.FileCreator.TrimEnd(' '), string.Empty);
                    AssertAreEqual(liFeSource.Version, expected[9]);
                    AssertAreEqual(liFeSource.AdobeStockLicenseState, expected[10]);
                    AssertAreEqual(liFeSource.HasFileOpenDescriptor, (bool)expected[11]);

                    if (liFeSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(liFeSource.CompId, -1);
                        AssertAreEqual(liFeSource.OriginalCompId, -1);
                        liFeSource.CompId = int.MaxValue;
                    }

                    liFeSource.FullPath = @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                    liFeSource.FileName = "rgb8_2x23.png";
                    liFeSource.ChildDocId = Guid.NewGuid().ToString();
                    liFeSource.Date = DateTime.Now;
                    liFeSource.AssetModTime = double.MaxValue;
                    liFeSource.FileSize = long.MaxValue;
                    liFeSource.FileType = "test";
                    liFeSource.FileCreator = "file";
                    AssertAreEqual((int)liFeSource.Length, expected[12]);
                }

                AssertAreEqual(lnkeResource.Length, length2);
                break;
            }
        }

        AssertIsTrue(lnkeResource != null);
    }
}

ExampleOfComplexLnkEResourceSupport(
    "OneReview-InDesign-RefreshPreviewIxD(2).psd",
    0x21ac,
    0x1db8,
    ComplexLnkEResourceSupportCases);
```

### 也可以看看

* class [LinkDataSource](../linkdatasource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
