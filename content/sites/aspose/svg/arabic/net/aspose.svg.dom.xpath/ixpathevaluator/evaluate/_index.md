---
title: Evaluate
second_title: Aspose.SVG لمرجع .NET API
description: بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن.
type: docs
weight: 30
url: /ar/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath المراد تحليلها وتقييمها. |
| contextNode | Node | ال`سياق الكلام` هي عقدة سياق لتقييم تعبير XPath هذا. إذا كان[`IXPathEvaluator`](../../ixpathevaluator) تم الحصول عليها عن طريق صب [`Document`](../../../aspose.svg.dom/document) ثم يجب أن يكون هذا مملوكًا لنفس المستند ويجب أن يكون [`Document`](../../../aspose.svg.dom/document) و[`Element`](../../../aspose.svg.dom/element) و[`Attr`](../../../aspose.svg.dom/attr) و[`Text`](../../../aspose.svg.dom/text) ، [`CDATASection`](../../../aspose.svg.dom/cdatasection) و[`Comment`](../../../aspose.svg.dom/comment) و[`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction) أو أوXPathNamespace العقدة. إذا كانت عقدة السياق هي ملف[`Text`](../../../aspose.svg.dom/text) أو [`CDATASection`](../../../aspose.svg.dom/cdatasection)، ثم يتم تفسير السياق على أنه عقدة النص المنطقي بأكملها كما يراها XPath ، إلا إذا كانت العقدة فارغة وفي هذه الحالة قد لا تعمل كسياق XPath. |
| resolver | IXPathNSResolver | ال`محلل` يسمح بترجمة جميع البادئات ، بما في ذلك `xml` بادئة مساحة الاسم ، ضمن تعبير XPath إلى مساحة الاسم المناسبة URIs. إذا تم تحديد ذلك على أنه`لا شيء` ، ستؤدي أي بادئة لمساحة الاسم داخل التعبير إلى في[`DOMException`](../../../aspose.svg.dom/domexception) تم إلقاؤهم مع الرمز`NAMESPACE_ERR`. |
| type | XPathResultType | إذا كان ملف`يكتب` تم تحديد ، ثم سيتم إرجاع النتيجة كـ من النوع المقابل. بالنسبة لنتائج XPath 1.0 ، يجب أن تكون هذه إحدى قيم [`XPathResultType`](../../xpathresulttype) تعداد. |
| result | Object | ال`نتيجة` يحدد كائن نتيجة محدد يمكن إعادة استخدامه وإعادته بهذه الطريقة. إذا تم تحديد هذا على أنه`لا شيء`أو أن التنفيذ لا يعيد استخدام النتيجة المحددة ، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0 ، سيكون هذا الكائن من النوع[`IXPathResult`](../../ixpathresult). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0 ، سيكون هذا الكائن من النوع[`IXPathResult`](../../ixpathresult).

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد[`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.svg.dom/domexception) | TYPE_ERR: يتم رفعه إذا تعذر تحويل النتيجة لإرجاع النوع المحدد . |
| [DOMException](../../../aspose.svg.dom/domexception) | NAMESPACE_ERR: يتم رفعه إذا كان التعبير يحتوي على بادئات مساحة الاسم والتي لا يمكن حلها بواسطة المحدد[`IXPathNSResolver`](../../ixpathnsresolver). |
| [DOMException](../../../aspose.svg.dom/domexception) | WRONG_DOCUMENT_ERR: العقدة من مستند لا يدعمه هذا [`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.svg.dom/domexception) | NOT_SUPPORTED_ERR: العقدة ليست نوعًا مسموحًا به كعقدة سياق XPath أو نوع الطلب غير مسموح به بواسطة هذا[`IXPathEvaluator`](../../ixpathevaluator). |

### أنظر أيضا

* interface [IXPathResult](../../ixpathresult)
* class [Node](../../../aspose.svg.dom/node)
* interface [IXPathNSResolver](../../ixpathnsresolver)
* enum [XPathResultType](../../xpathresulttype)
* interface [IXPathEvaluator](../../ixpathevaluator)
* مساحة الاسم [Aspose.Svg.Dom.XPath](../../ixpathevaluator)
* المجسم [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
