---
title: CurrentScale
second_title: Справочник по Aspose.SVG для .NET API
description: В самом внешнем элементе svg этот атрибут указывает текущий коэффициент масштабирования по отношению к исходному виду чтобы учитывать операции увеличения и панорамирования выполняемые пользователем как описано в разделе Увеличение и панорамирование. Атрибуты DOM currentScale и currentTranslate эквивалентны матрице 2x3 abcdef  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Если включено увеличение т. е. zoomAndPan  увеличение эффект будет таким как если бы дополнительное преобразование было размещено на самом внешнем уровне фрагмента документа SVG т. е. за пределами самого внешнего элемента svg. При доступе к элемент svg который не является самым внешним элементом svg не определено какое поведение имеет этот атрибут.
type: docs
weight: 10
url: /ru/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

В самом внешнем элементе svg этот атрибут указывает текущий коэффициент масштабирования по отношению к исходному виду, чтобы учитывать операции увеличения и панорамирования, выполняемые пользователем, как описано в разделе «Увеличение и панорамирование». Атрибуты DOM currentScale и currentTranslate эквивалентны матрице 2x3 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Если включено «увеличение» (т. е. zoomAndPan = «увеличение»), эффект будет таким, как если бы дополнительное преобразование было размещено на самом внешнем уровне фрагмента документа SVG (т. е. за пределами самого внешнего элемента svg). При доступе к элемент 'svg', который не является самым внешним элементом svg, не определено, какое поведение имеет этот атрибут.

```csharp
public float CurrentScale { get; set; }
```

### Стоимость имущества

Текущий масштаб.

### Смотрите также

* class [SVGSVGElement](../../svgsvgelement)
* пространство имен [Aspose.Svg](../../svgsvgelement)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
