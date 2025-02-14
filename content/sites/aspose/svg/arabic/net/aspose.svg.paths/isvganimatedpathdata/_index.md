---
title: ISVGAnimatedPathData
second_title: Aspose.SVG لمرجع .NET API
description: تدعم واجهة SVGAnimatedPathData العناصر التي لها سمة d التي تحتفظ ببيانات مسار SVG  وتدعم القدرة على تحريك تلك السمة.
type: docs
weight: 2450
url: /ar/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

تدعم واجهة SVGAnimatedPathData العناصر التي لها سمة 'd' التي تحتفظ ببيانات مسار SVG ، وتدعم القدرة على تحريك تلك السمة.

```csharp
public interface ISVGAnimatedPathData
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist) { get; } | يوفر الوصول إلى المحتويات المتحركة الحالية للسمة "d" في نموذج يطابق واحدًا لواحد مع صيغة SVG. إذا تم تحريك السمة أو الخاصية المحددة ، فإنها تحتوي على القيمة المتحركة الحالية للسمة أو الخاصية ، ويتم قراءة كل من الكائن نفسه ومحتوياته فقط. إذا لم يتم تحريك السمة أو الخاصية المحددة حاليًا ، فستحتوي على نفس القيمة مثل pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist) { get; } | يوفر الوصول إلى المحتويات الأساسية (أي الثابتة) للسمة "d" في نموذج يطابق واحدًا لواحد مع صيغة SVG. وبالتالي ، إذا كانت السمة 'd' تحتوي على أمر "الحركة المطلقة (M)" وأمر "arcto (A) المطلق" ، فسيكون لدى pathSegList إدخالان: SVG_PATHSEG_MOVETO_ABS و SVG_PATHSEG_ARC_ABS. |

### أنظر أيضا

* مساحة الاسم [Aspose.Svg.Paths](../../aspose.svg.paths)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
