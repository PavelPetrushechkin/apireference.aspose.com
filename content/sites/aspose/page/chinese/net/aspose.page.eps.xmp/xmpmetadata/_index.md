---
title: XmpMetadata
second_title: Aspose.Page for .NET API 参考
description: 提供对 XMP 元数据流的访问
type: docs
weight: 130
url: /zh/net/aspose.page.eps.xmp/xmpmetadata/
---
## XmpMetadata class

提供对 XMP 元数据流的访问。

```csharp
public sealed class XmpMetadata : IDictionary<string, XmpValue>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.page.eps.xmp/xmpmetadata/count) { get; } | 获取集合中元素的计数。 |
| [IsFixedSize](../../aspose.page.eps.xmp/xmpmetadata/isfixedsize) { get; } | 检查colleciton 是否有固定大小。 |
| [IsReadOnly](../../aspose.page.eps.xmp/xmpmetadata/isreadonly) { get; } | 检查集合是否是只读的。 |
| [IsSynchronized](../../aspose.page.eps.xmp/xmpmetadata/issynchronized) { get; } | 检查收集是否同步。 |
| [Item](../../aspose.page.eps.xmp/xmpmetadata/item) { get; set; } | 从元数据中获取或设置数据。 |
| [Keys](../../aspose.page.eps.xmp/xmpmetadata/keys) { get; } | 获取元数据键的集合。 |
| [NamespaceManager](../../aspose.page.eps.xmp/xmpmetadata/namespacemanager) { get; } | 获取命名空间管理器。 |
| [SyncRoot](../../aspose.page.eps.xmp/xmpmetadata/syncroot) { get; } | 获取集合同步对象。 |
| [Values](../../aspose.page.eps.xmp/xmpmetadata/values) { get; } | 获取元数据中的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add)(KeyValuePair&lt;string, XmpValue&gt;) | 将键和值对添加到字典中。 |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add_2)(string, object) | 为元数据增加价值。 |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add_1)(string, XmpValue) | 为元数据增加价值。 |
| [AddArrayItem](../../aspose.page.eps.xmp/xmpmetadata/addarrayitem#addarrayitem)(string, XmpValue) | 将值添加到数组中。该值将添加到数组的末尾。 |
| [AddArrayItem](../../aspose.page.eps.xmp/xmpmetadata/addarrayitem#addarrayitem_1)(string, int, XmpValue) | 按指定索引将值添加到数组中。 |
| [AddNamedValue](../../aspose.page.eps.xmp/xmpmetadata/addnamedvalue)(string, string, XmpValue) | 将命名值添加到结构中。 |
| [Clear](../../aspose.page.eps.xmp/xmpmetadata/clear)() | 清除元数据。 |
| [Contains](../../aspose.page.eps.xmp/xmpmetadata/contains#contains)(KeyValuePair&lt;string, XmpValue&gt;) | 检查指定的键值对是否包含在字典中。 |
| [Contains](../../aspose.page.eps.xmp/xmpmetadata/contains#contains_1)(string) | 检查密钥是否包含在元数据中。 |
| [ContainsKey](../../aspose.page.eps.xmp/xmpmetadata/containskey)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.page.eps.xmp/xmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) | 将集合的元素复制到数组中。 |
| [GetEnumerator](../../aspose.page.eps.xmp/xmpmetadata/getenumerator)() | 返回字典枚举器。 |
| [GetNamespaceUriByPrefix](../../aspose.page.eps.xmp/xmpmetadata/getnamespaceuribyprefix)(string) | 按前缀返回命名空间 URI。 |
| [GetPrefixByNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/getprefixbynamespaceuri)(string) | 按命名空间 URI 返回前缀。 |
| [RegisterNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/registernamespaceuri#registernamespaceuri)(string, string) | 注册命名空间 URI. |
| [RegisterNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/registernamespaceuri#registernamespaceuri_1)(string, string, string) | 注册命名空间 URI. |
| [Remove](../../aspose.page.eps.xmp/xmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 从集合中删除键/值对。 |
| [Remove](../../aspose.page.eps.xmp/xmpmetadata/remove#remove_1)(string) | 从元数据中删除条目。 |
| [SetArrayItem](../../aspose.page.eps.xmp/xmpmetadata/setarrayitem)(string, int, XmpValue) | 在数组中设置值。以前的值将被新的值替换。 |
| [SetNamedValue](../../aspose.page.eps.xmp/xmpmetadata/setnamedvalue)(string, string, XmpValue) | 将命名值设置为结构。以前的命名值，如果已经存在，将被替换为新的。 |
| [TryGetValue](../../aspose.page.eps.xmp/xmpmetadata/trygetvalue)(string, out XmpValue) | 尝试在字典中查找键，如果找到则检索值。 |

### 也可以看看

* class [XmpValue](../xmpvalue)
* 命名空间 [Aspose.Page.EPS.XMP](../../aspose.page.eps.xmp)
* 部件 [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
