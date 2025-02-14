---
title: PathStructure
second_title: Aspose.PSD for .NET API 参考
description: 路径结构
type: docs
weight: 3160
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
## PathStructure class

路径结构。

```csharp
public sealed class PathStructure : OSTypeStructure
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathStructure](pathstructure)(ClassID) | 初始化[`PathStructure`](../pathstructure)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key) { get; } | 获取结构键。 |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | 获取或设置键名。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length) { get; } | 获取[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)字节长度。 |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path) { get; set; } | 获取或设置路径。 |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix) { get; set; } | 获取或设置路径前缀 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | 获取标头长度。 |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | 将结构保存到指定的流容器。 |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | 将结构保存到指定的流容器。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey) | 标识结构键。 |

### 例子

以下代码演示了使用 PathStructure 结构加载文件的能力。

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 也可以看看

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
