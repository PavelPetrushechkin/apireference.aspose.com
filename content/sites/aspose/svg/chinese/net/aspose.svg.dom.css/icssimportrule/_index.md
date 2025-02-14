---
title: ICSSImportRule
second_title: Aspose.SVG for .NET API 参考
description: CSSImportRule 接口表示CSS 样式表中的import 规则 import 规则用于从其他样式表中导入样式规则
type: docs
weight: 560
url: /zh/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule 接口表示CSS 样式表中的@import 规则。 @import 规则用于从其他样式表中导入样式规则。

```csharp
public interface ICSSImportRule : ICSSRule
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href) { get; } | 要导入的样式表的位置。该属性将不包含 URI. 周围的“url(...)”说明符 |
| [Media](../../aspose.svg.dom.css/icssimportrule/media) { get; } | 可以使用此样式表的媒体类型列表。 |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet) { get; } | 此规则引用的样式表（如果已加载）。如果样式表尚未加载或将不会加载（例如，如果样式表用于用户代理不支持的媒体类型），则此属性的值为 null。 |

### 也可以看看

* interface [ICSSRule](../icssrule)
* 命名空间 [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
