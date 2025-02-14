---
title: ICSSStyleSheet
second_title: Aspose.HTML for .NET API Reference
description: The CSSStyleSheet interface represents a single CSS stylesheet and lets you inspect and modify the list of rules contained in the stylesheet. It inherits properties and methods from its parent StyleSheet./istylesheet.
type: docs
weight: 520
url: /net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

The CSSStyleSheet interface represents a single CSS stylesheet, and lets you inspect and modify the list of rules contained in the stylesheet. It inherits properties and methods from its parent, [`StyleSheet`](../istylesheet).

A stylesheet consists of a collection of [`CSSRule`](../icssrule) objects representing each of the rules in the stylesheet. The rules are contained in a [`CSSRuleList`](../icssrulelist), which can be obtained from the stylesheet's cssRules property.

For example, one rule might be a [`CSSStyleRule`](../icssstylerule) object containing a style such as

```csharp
h1, h2 {   font-size: 16pt; }
```

Another rule might be an at-rule such as @import or @media, and so forth.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Properties

| Name | Description |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules) { get; } | The read-only CSSStyleSheet property cssRules returns a live [`CSSRuleList`](../icssrulelist) which provides a real-time, up-to-date list of every CSS rule which comprises the stylesheet. Each item in the list is a [`CSSRule`](../icssrule) defining a single rule. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule) { get; } | The read-only CSSStyleSheet property ownerRule returns the [`CSSImportRule`](../icssimportrule) corresponding to the @import at-rule which imported the stylesheet into the document. If the stylesheet wasn't imported into the document using @import, the returned value is null. |

## Methods

| Name | Description |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule)(int) | The [`CSSStyleSheet`](../icssstylesheet) method deleteRule() removes a rule from the stylesheet object. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule)(string, int) | The CSSStyleSheet.insertRule() method inserts a new CSS rule into the current style sheet, with some restrictions. |

### Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### See Also

* interface [IStyleSheet](../istylesheet)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
