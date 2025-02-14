---
title: CalculationPrecisionStrategy
second_title: Aspose.Cells for .NET API Reference
description: Enumerates strategies for handling calculation precision. Because of the precision issue of IEEE 754 Floating-Point Arithmetic some seemingly simple formulas may not be calculated as the expected result. Such as formula -0.450.430.02 when calculating operands by  operator directly the result is not zero. For such kind of precision issue some special strategies may give the expected result.
type: docs
weight: 220
url: /net/aspose.cells/calculationprecisionstrategy/
---
## CalculationPrecisionStrategy enumeration

Enumerates strategies for handling calculation precision. Because of the precision issue of IEEE 754 Floating-Point Arithmetic, some "seemingly simple" formulas may not be calculated as the expected result. Such as formula "=-0.45+0.43+0.02", when calculating operands by '+' operator directly, the result is not zero. For such kind of precision issue, some special strategies may give the expected result.

```csharp
public enum CalculationPrecisionStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No strategy applied on calculation. When calculating just use the original double value as operand and return the result directly. Most efficient for performance and applicable for most cases. |
| Round | `1` | Rounds the calculation result according with significant digits. |
| Decimal | `2` | Uses decimal as operands when possible. Most inefficient for performance. |

### See Also

* namespace [Aspose.Cells](../../aspose.cells)
* assembly [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->
