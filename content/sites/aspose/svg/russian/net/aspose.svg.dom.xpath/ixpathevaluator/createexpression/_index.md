---
title: CreateExpression
second_title: Справочник по Aspose.SVG для .NET API
description: Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно  когда выражение будет повторно использоваться в приложении поскольку позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все префиксы пространства имен которые встречаются в выражении.
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно , когда выражение будет повторно использоваться в приложении, поскольку позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все префиксы пространства имен, которые встречаются в выражении.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка выражения XPath для анализа. |
| resolver | IXPathNSResolver | `резольвер` разрешает перевод всех префиксов, включая`XML` префикс пространства имен в выражении XPath в соответствующие URI пространства имен. Если это указано как`нулевой` , любой префикс пространства имен в выражении приведет к[`DOMException`](../../../aspose.svg.dom/domexception) быть брошенным с кодом`NAMESPACE_ERR`. |

### Возвращаемое значение

Скомпилированная форма выражения XPath.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception) | INVALID_EXPRESSION_ERR: Возникает, если выражение не является допустимым в соответствии с правилами[`IXPathEvaluator`](../../ixpathevaluator). |
| [DOMException](../../../aspose.svg.dom/domexception) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пространства имен , которые не могут быть разрешены указанным[`IXPathNSResolver`](../../ixpathnsresolver). |

### Смотрите также

* interface [IXPathExpression](../../ixpathexpression)
* interface [IXPathNSResolver](../../ixpathnsresolver)
* interface [IXPathEvaluator](../../ixpathevaluator)
* пространство имен [Aspose.Svg.Dom.XPath](../../ixpathevaluator)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
