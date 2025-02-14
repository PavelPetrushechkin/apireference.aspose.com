---
title: GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API 参考
description: 获取第一个找到的适合指定的支持描述符stream和可选的loadOptions .
type: docs
weight: 40
url: /zh/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

获取第一个找到的适合指定的支持描述符*stream*和可选的*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 负载选项。 |

### 返回值

支持指定的加载器描述符*stream*和*loadOptions*如果没有找到这样的描述符，则为 null。

### 评论

第一个加载器描述符实际上是最后注册的。

### 也可以看看

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* 命名空间 [Aspose.PSD](../../imageloadersregistry)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
