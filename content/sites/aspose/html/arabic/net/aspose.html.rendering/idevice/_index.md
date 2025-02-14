---
title: IDevice
second_title: Aspose.HTML لمرجع .NET API
description: يحدد الأساليب والخصائص التي تدعم العرض المخصص للعناصر الرسومية مثل المسارات والنصوص والصور.
type: docs
weight: 4270
url: /ar/net/aspose.html.rendering/idevice/
---
## IDevice interface

يحدد الأساليب والخصائص التي تدعم العرض المخصص للعناصر الرسومية مثل المسارات والنصوص والصور.

```csharp
public interface IDevice : IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext) { get; } | يحصل على سياق الرسم . |
| [Options](../../aspose.html.rendering/idevice/options) { get; } | يحصل على خيارات التقديم . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect)(RectangleF) | إلحاق مستطيل بالمسار الحالي كمسار فرعي كامل. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument)(Document) | يبدأ عرض المستند. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement)(Element, RectangleF) | يبدأ عرض العنصر. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage)(SizeF) | يبدأ عرض الصفحة الجديدة. |
| [Clip](../../aspose.html.rendering/idevice/clip)(FillMode) | يعدل مسار القطع الحالي من خلال تقاطعه مع المسار الحالي ، باستخدام قاعدة FillMode لتحديد المنطقة المراد تعبئتها. تنهي هذه الطريقة المسار الحالي. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath)() | لإغلاق المسار الفرعي الحالي بإلحاق مقطع بخط مستقيم من النقطة الحالية إلى نقطة بداية المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل ، فلن يفعل "ClosePath" شيئًا . ينهي عامل التشغيل هذا المسار الفرعي الحالي. يؤدي إلحاق مقطع آخر بالمسار الحالي إلى بدء مسار فرعي جديد ، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي تم الوصول إليها بواسطة طريقة "ClosePath" . |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto)(PointF, PointF, PointF) | لإلحاق منحنى بيزير مكعب بالمسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt3 ، باستخدام pt1 و pt2 كنقاط تحكم Bézier. النقطة الحالية الجديدة هي pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage)(byte[], ImageType, RectangleF) | يرسم الصورة المحددة . |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument)() | ينتهي عرض المستند. |
| [EndElement](../../aspose.html.rendering/idevice/endelement)(Element) | ينتهي عرض العنصر. |
| [EndPage](../../aspose.html.rendering/idevice/endpage)() | ينتهي عرض الصفحة الحالية. |
| [Fill](../../aspose.html.rendering/idevice/fill)(FillMode) | يملأ المنطقة بأكملها المحاطة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة ، فإنه يملأ الدواخل لجميع المسارات الفرعية ، تعتبر معًا. تنهي هذه الطريقة المسار الحالي. |
| [FillText](../../aspose.html.rendering/idevice/filltext)(string, PointF) | يملأ السلسلة النصية المحددة في المكان المحدد. |
| [Flush](../../aspose.html.rendering/idevice/flush)() | مسح جميع البيانات لإخراج التدفق. |
| [LineTo](../../aspose.html.rendering/idevice/lineto)(PointF) | لإلحاق مقطع خط مستقيم من النقطة الحالية بالنقطة (نقطة). النقطة الحالية الجديدة هي pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto)(PointF) | يبدأ مسارًا فرعيًا جديدًا عن طريق تحريك النقطة الحالية إلى إحداثيات المعلمة pt ، مع حذف أي مقطع خط متصل. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo" ، فإن "MoveTo" الجديد يتجاوزها ؛ لا توجد آثار لعملية "MoveTo" السابقة في المسار. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إخراجه من المكدس. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext)() | يدفع نسخة من سياق الرسوم بأكمله إلى المكدس. |
| [Stroke](../../aspose.html.rendering/idevice/stroke)() | رسم خط بطول المسار الحالي. يتبع الخط المحدد كل مقطع مستقيم أو منحني في المسار ، متمركزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل من المسارات الفرعية للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill)(FillMode) | ضربات وملء المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext)(string, PointF) | ضربات السلسلة النصية المحددة في الموقع المحدد. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Rendering](../../aspose.html.rendering)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
