---
title: XpsFillRule
second_title: Справочник по Aspose.Page для .NET API
description: Допустимые значения свойства FillRule элемента PathGeometry.
type: docs
weight: 3010
url: /ru/net/aspose.page.xps.xpsmodel/xpsfillrule/
---
## XpsFillRule enumeration

Допустимые значения свойства FillRule элемента PathGeometry.

```csharp
public enum XpsFillRule
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| EvenOdd | `0` | Это правило определяет «внутренность» точки на холсте, проводя луч из точки в бесконечность в любом направлении и подсчитывая количество сегментов от заданной формы, которые пересекает луч. Если это число нечетное, точка находится внутри ; если четное, то точка снаружи. |
| NonZero | `1` | Это правило определяет «внутренность» точки на холсте, проводя луч от точки до бесконечности в любом направлении, а затем исследуя места, где сегмент фигуры пересекает луч. Начиная с нуля, прибавляйте единицу каждый раз, когда сегмент пересекает луч слева направо, и вычитайте единицу каждый раз, когда сегмент пути пересекает луч справа налево. После подсчета пересечений, , если результат равен нулю, то точка находится вне пути; в противном случае он внутри. |

### Смотрите также

* пространство имен [Aspose.Page.XPS.XpsModel](../../aspose.page.xps.xpsmodel)
* сборка [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
