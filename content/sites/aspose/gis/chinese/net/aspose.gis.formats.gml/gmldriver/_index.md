---
title: GmlDriver
second_title: Aspose.GIS for .NET API 参考
description: GML 格式的驱动程序
type: docs
weight: 290
url: /zh/net/aspose.gis.formats.gml/gmldriver/
---
## GmlDriver class

GML 格式的驱动程序。

```csharp
public sealed class GmlDriver : FileDriver
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.gml/gmldriver/cancreatedatasets) { get; } | 获取一个值，该值指示此驱动程序是否可以创建数据集。 |
| override [CanCreateLayers](../../aspose.gis.formats.gml/gmldriver/cancreatelayers) { get; } | 获取一个值，该值指示此驱动程序是否可以创建矢量图层。 |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets) { get; } | 获取一个值，该值指示此驱动程序是否可以打开数据集。 |
| override [CanOpenLayers](../../aspose.gis.formats.gml/gmldriver/canopenlayers) { get; } | 获取一个值，该值指示此驱动程序是否可以打开矢量图层。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(AbstractPath) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string) | 创建一个数据集。 |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset)(AbstractPath, DriverOptions) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string, DriverOptions) | 创建一个数据集。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, DriverOptions) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer#createlayer_7)(string, GmlOptions) | 创建一个图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| override [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | 创建一个图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer#createlayer_8)(string, GmlOptions, SpatialReferenceSystem) | 创建一个图层并打开它以添加新功能。 |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer)(AbstractPath, DriverOptions) | 打开一个图层进行编辑。 |
| [EditLayer](../../aspose.gis/filedriver/editlayer)(string, DriverOptions) | 打开一个图层进行编辑。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(AbstractPath) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string) | 打开数据集。 |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset)(AbstractPath, DriverOptions) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string, DriverOptions) | 打开数据集。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(AbstractPath) | 打开图层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string) | 打开图层进行读取。 |
| override [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer#openlayer_1)(AbstractPath, DriverOptions) | 打开一个层进行读取。 |
| [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer#openlayer_2)(AbstractPath, GmlOptions) | 打开一个层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string, DriverOptions) | 打开图层进行读取。 |
| [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer#openlayer_5)(string, GmlOptions) | 打开一个层进行读取。 |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.gml/gmldriver/supportsspatialreferencesystem)(SpatialReferenceSystem) | 确定驱动程序是否支持指定的空间参考系统。 |

### 也可以看看

* class [FileDriver](../../aspose.gis/filedriver)
* 命名空间 [Aspose.Gis.Formats.Gml](../../aspose.gis.formats.gml)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
