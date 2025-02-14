---
title: Superscript
second_title: Aspose.Sildes for .NET API Reference
description: Specifies a supersript argument that for example in the case of an integral sets the upper limit
type: docs
weight: 50
url: /net/aspose.slides.mathtext/imathnaryoperator/superscript/
---
## IMathNaryOperator.Superscript property

Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit

```csharp
public IMathElement Superscript { get; }
```

### Examples

Example:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
IMathElement superscriptArg = naryOperator.Superscript;
```

### See Also

* interface [IMathElement](../../imathelement)
* interface [IMathNaryOperator](../../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../imathnaryoperator)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
