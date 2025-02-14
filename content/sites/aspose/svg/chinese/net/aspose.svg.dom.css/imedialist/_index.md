---
title: IMediaList
second_title: Aspose.SVG for .NET API 参考
description: MediaList 接口提供了一个有序的媒体集合的抽象没有定义或限制如何实现这个集合空列表与包含介质all的列表相同
type: docs
weight: 730
url: /zh/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

MediaList 接口提供了一个有序的媒体集合的抽象，没有定义或限制如何实现这个集合。空列表与包含介质“all”的列表相同。

```csharp
public interface IMediaList : IEnumerable<string>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item) { get; } | 返回列表中的索引。如果 index 大于或等于列表中的媒体数量，则返回 null. 媒体索引。 |
| [Length](../../aspose.svg.dom.css/imedialist/length) { get; } | 列表中的媒体数量。有效媒体的范围是 0 到长度 1（含）。 |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext) { get; } | 媒体列表的可解析文本表示。这是一个以逗号分隔的媒体列表。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium)(string) | 将媒体 newMedium 添加到列表的末尾。如果已经使用了newMedium，则先将其移除。 |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium)(string) | 从列表中删除 oldMedium 指示的介质。 |

### 也可以看看

* 命名空间 [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
