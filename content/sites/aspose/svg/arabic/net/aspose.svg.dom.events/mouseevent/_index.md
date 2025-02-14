---
title: MouseEvent
second_title: Aspose.SVG لمرجع .NET API
description: توفر واجهة MouseEvent معلومات سياقية محددة مرتبطة بأحداث الماوس.
type: docs
weight: 990
url: /ar/net/aspose.svg.dom.events/mouseevent/
---
## MouseEvent class

توفر واجهة MouseEvent معلومات سياقية محددة مرتبطة بأحداث الماوس.

```csharp
public class MouseEvent : UIEvent
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MouseEvent](mouseevent#constructor)(string) | يقوم بتهيئة مثيل جديد لملف[`MouseEvent`](../mouseevent) فئة . |
| [MouseEvent](mouseevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | يقوم بتهيئة مثيل جديد لملف[`MouseEvent`](../mouseevent) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AltKey](../../aspose.svg.dom.events/mouseevent/altkey) { get; } | الرجوع إلى سمة altKey . |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Button](../../aspose.svg.dom.events/mouseevent/button) { get; } | أثناء أحداث الماوس الناتجة عن الضغط المنخفض أو تحرير زر الماوس ، يجب استخدام الزر للإشارة إلى زر جهاز المؤشر الذي تغير حالته. |
| [Buttons](../../aspose.svg.dom.events/mouseevent/buttons) { get; } | أثناء أي أحداث للماوس ، يجب استخدام الأزرار للإشارة إلى مجموعة أزرار الماوس التي يتم الضغط عليها حاليًا ، ويتم التعبير عنها كقناع بت. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [ClientX](../../aspose.svg.dom.events/mouseevent/clientx) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة إلى منفذ العرض المرتبط بالحدث . |
| [ClientY](../../aspose.svg.dom.events/mouseevent/clienty) { get; } | الإحداثي الرأسي الذي وقع فيه الحدث بالنسبة إلى منفذ العرض المرتبط بالحدث . |
| [CtrlKey](../../aspose.svg.dom.events/mouseevent/ctrlkey) { get; } | الرجوع إلى سمة ctrlKey . |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget) ملك من[`IEventListener`](../ieventlistener) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [Detail](../../aspose.svg.dom.events/uievent/detail) { get; } | تحديد بعض المعلومات التفصيلية حول الحدث ، اعتمادًا على نوع الحدث. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [MetaKey](../../aspose.svg.dom.events/mouseevent/metakey) { get; } | الرجوع إلى سمة metaKey . |
| [RelatedTarget](../../aspose.svg.dom.events/mouseevent/relatedtarget) { get; } | يُستخدم لتحديد هدف EventTarget ثانوي مرتبط بحدث واجهة المستخدم ، اعتمادًا على نوع الحدث. |
| [ScreenX](../../aspose.svg.dom.events/mouseevent/screenx) { get; } | الإحداثي الأفقي الذي وقع فيه الحدث بالنسبة إلى أصل نظام إحداثيات الشاشة. |
| [ScreenY](../../aspose.svg.dom.events/mouseevent/screeny) { get; } | الإحداثي الرأسي الذي حدث عنده الحدث بالنسبة إلى أصل نظام إحداثيات الشاشة. |
| [ShiftKey](../../aspose.svg.dom.events/mouseevent/shiftkey) { get; } | الرجوع إلى سمة shiftKey . |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../ieventtarget) الذي تم إرسال الحدث إليه في الأصل. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة للعصر) الذي تم فيه إنشاء الحدث . نظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومات ، فقد لا يكون الطابع الزمني متاحًا لجميع الأحداث. ، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0: 0: 0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML . |
| [View](../../aspose.svg.dom.events/uievent/view) { get; } | تحدد سمة العرض النافذة التي تم إنشاء الحدث منها. يجب أن تكون القيمة غير المهيأة لهذه السمة خالية. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | ملف[`InitEvent`](../event/initevent) يتم استخدام طريقة لتهيئة قيمة[`Event`](../event) تم إنشاؤه من خلال [`IDocumentEvent`](../idocumentevent) الواجهة . |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | إذا كان الحدث قابلاً للإلغاء ، فإن ملف[`PreventDefault`](../event/preventdefault) يتم استخدام الطريقة للدلالة على أن الحدث سيتم إلغاؤه ، مما يعني أن أي إجراء افتراضي يتم اتخاذه عادةً بواسطة التنفيذ نتيجة للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعين للأحداث مسجل بعد الحدث الحالي وعندما يتم إرساله في شجرة يمنع أيضًا الحدث من الوصول إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | ملف[`StopPropagation`](../event/stoppropagation) الطريقة المستخدمة لمنع المزيد من الانتشار لحدث ما أثناء تدفق الحدث. |

### أنظر أيضا

* class [UIEvent](../uievent)
* مساحة الاسم [Aspose.Svg.Dom.Events](../../aspose.svg.dom.events)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
