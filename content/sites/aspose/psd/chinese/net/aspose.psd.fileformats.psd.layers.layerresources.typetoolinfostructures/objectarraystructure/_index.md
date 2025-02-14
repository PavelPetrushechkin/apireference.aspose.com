---
title: ObjectArrayStructure
second_title: Aspose.PSD for .NET API 参考
description: 定义通常持有的 ObjectArrayStructure 类UnitArrayStructure./unitarraystructurearray. 用于PSD文件资源如PlLd Resource和SoLd Resource.
type: docs
weight: 3140
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
## ObjectArrayStructure class

定义通常持有的 ObjectArrayStructure 类[`UnitArrayStructure`](../unitarraystructure)array. 用于PSD文件资源，如PlLd Resource和SoLd Resource.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure#constructor_1)(string, string, OSTypeStructure[]) | 初始化[`ObjectArrayStructure`](../objectarraystructure)类. |
| [ObjectArrayStructure](objectarraystructure#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | 初始化[`ObjectArrayStructure`](../objectarraystructure)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid) { get; set; } | 获取或设置对象数组类ID。 |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname) { get; set; } | 获取或设置对象数组类名。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key) { get; } | 获取对象数组结构键。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | 获取或设置键名。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length) { get; } | 获取[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)字节长度。 |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount) { get; } | 获取对象数组子结构计数。 |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures) { get; set; } | 获取或设置结构数组的副本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | 获取标头长度。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | 将结构保存到指定的流容器。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | 将结构保存到指定的流容器。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey) | 标识“ObAr”结构键。 |

### 例子

以下代码演示了对 ObAr 和 UnFl 签名的支持。

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### 也可以看看

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
