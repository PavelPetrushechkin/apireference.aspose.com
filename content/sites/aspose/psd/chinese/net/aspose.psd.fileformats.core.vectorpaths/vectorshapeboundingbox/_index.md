---
title: VectorShapeBoundingBox
second_title: Aspose.PSD for .NET API 参考
description: 定义矢量形状边界框类
type: docs
weight: 1430
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/
---
## VectorShapeBoundingBox class

定义矢量形状边界框类。

```csharp
public sealed class VectorShapeBoundingBox
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [VectorShapeBoundingBox](vectorshapeboundingbox)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bottom) { get; set; } | 获取或设置底部。 |
| [Bounds](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/bounds) { get; set; } | 获取或设置形状边界框的边界。 |
| [Left](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/left) { get; set; } | 获取或设置左边。 |
| [QuadVersion](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/quadversion) { get; set; } | 获取或设置单位值 quad 版本。 |
| [Right](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/right) { get; set; } | 获取或设置权限。 |
| [Top](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeboundingbox/top) { get; set; } | 获取或设置顶部。 |

### 例子

此示例演示了加载和保存具有形状层和矢量路径的 PSD 图像可以正常工作。

```csharp
[C#]

// 这个例子演示了加载和保存带有形状层和矢量路径的 PSD 图像可以正常工作。
string sourcePath = "vectorShapes.psd";
string outputFilePath = "output_vectorShapes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourcePath))
{
    var resource = GetVogkResource(image);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    var originalSetting = resource.ShapeOriginSettings[0];
    originalSetting.IsShapeInvalidated = true;
    resource.ShapeOriginSettings = new[]
    {
        originalSetting,
        new VectorShapeOriginSettings()
        {
            OriginIndex = 1,
            OriginResolution = 144,
            OriginType = 4,
            OriginShapeBox = new VectorShapeBoundingBox()
            {
                Bounds = Rectangle.FromLeftTopRightBottom(10, 15, 40, 70)
            }
        },
        new VectorShapeOriginSettings()
        {
            OriginIndex = 2,
            OriginResolution = 301,
            OriginType = 5,
            OriginRadiiRectangle = new VectorShapeRadiiRectangle()
            {
                TopLeft = 2,
                TopRight = 6,
                BottomLeft = 23,
                BottomRight = 42,
                QuadVersion = 1
            }
        }
    };

    image.Save(outputFilePath, new PsdOptions());
}

using (PsdImage image = (PsdImage)Image.Load(outputFilePath))
{
    var resource = GetVogkResource(image);
    AssertAreEqual(3, resource.ShapeOriginSettings.Length);

    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(true, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsShapeInvalidated);

    setting = resource.ShapeOriginSettings[1];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(1, setting.OriginIndex);
    AssertAreEqual(144.0, setting.OriginResolution);
    AssertAreEqual(4, setting.OriginType);
    AssertAreEqual(Rectangle.FromLeftTopRightBottom(10, 15, 40, 70), setting.OriginShapeBox.Bounds);

    setting = resource.ShapeOriginSettings[2];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(false, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(true, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(2, setting.OriginIndex);
    AssertAreEqual(301.0, setting.OriginResolution);
    AssertAreEqual(5, setting.OriginType);
    AssertAreEqual(2.0, setting.OriginRadiiRectangle.TopLeft);
    AssertAreEqual(6.0, setting.OriginRadiiRectangle.TopRight);
    AssertAreEqual(23.0, setting.OriginRadiiRectangle.BottomLeft);
    AssertAreEqual(42.0, setting.OriginRadiiRectangle.BottomRight);
    AssertAreEqual(1, setting.OriginRadiiRectangle.QuadVersion);
}

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResource not found.");
    }

    return resource;
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
