---
title: TimeEvent
second_title: Aspose.SVG لمرجع .NET API
description: توفر واجهة TimeEvent معلومات سياقية محددة مرتبطة بأحداث الوقت. الأنواع المختلفة من الأحداث التي يمكن أن تحدث هي startEvent و endEvent و RepEvent.
type: docs
weight: 1630
url: /ar/net/aspose.svg.events/timeevent/
---
## TimeEvent class

توفر واجهة TimeEvent معلومات سياقية محددة مرتبطة بأحداث الوقت. الأنواع المختلفة من الأحداث التي يمكن أن تحدث هي: startEvent و endEvent و RepEvent.

```csharp
public class TimeEvent : Event
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bubbles](../../aspose.svg.dom.events/event/bubbles) { get; } | يُستخدم للإشارة إلى ما إذا كان الحدث عبارة عن حدث فقاعات أم لا. إذا كان الحدث يمكن أن ينفجر ، تكون القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [Cancelable](../../aspose.svg.dom.events/event/cancelable) { get; } | يُستخدم للإشارة إلى ما إذا كان يمكن منع إجراء افتراضي لحدث أم لا. إذا كان من الممكن منع الإجراء الافتراضي ، كانت القيمة صحيحة ، وإلا تكون القيمة خاطئة. |
| [CurrentTarget](../../aspose.svg.dom.events/event/currenttarget) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget) ملك من[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) يتم حاليًا معالجة الصورة . هذا مفيد بشكل خاص أثناء الالتقاط والفقاعات. |
| [DefaultPrevented](../../aspose.svg.dom.events/event/defaultprevented) { get; } | إرجاع صحيح إذا تم استدعاء PreventionDefault () بينما تكون قيمة السمة القابلة للإلغاء صحيحة ، والخطأ في الحالات الأخرى. |
| [Detail](../../aspose.svg.events/timeevent/detail) { get; } | تحديد بعض المعلومات التفصيلية حول الحدث ، اعتمادًا على نوع الحدث. بالنسبة لنوع الحدث هذا ، يشير إلى رقم التكرار للرسوم المتحركة. |
| [EventPhase](../../aspose.svg.dom.events/event/eventphase) { get; } | يُستخدم للإشارة إلى أي مرحلة من مراحل تدفق الأحداث يتم تقييمها حاليًا. |
| [IsTrusted](../../aspose.svg.dom.events/event/istrusted) { get; } | يجب أن ترجع السمة isTrusted القيمة التي تمت تهيئتها إليها. عند إنشاء حدث ، يجب تهيئة السمة إلى false . |
| [Target](../../aspose.svg.dom.events/event/target) { get; } | يُستخدم للإشارة إلى ملف[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget) الذي تم إرسال الحدث إليه في الأصل. |
| [TimeStamp](../../aspose.svg.dom.events/event/timestamp) { get; } | يُستخدم لتحديد الوقت (بالملي ثانية بالنسبة للعصر) الذي تم فيه إنشاء الحدث . نظرًا لأن بعض الأنظمة قد لا توفر هذه المعلومات ، فقد لا يكون الطابع الزمني متاحًا لجميع الأحداث. ، سيتم إرجاع القيمة 0. أمثلة على وقت الحقبة هي وقت بدء النظام أو 0: 0: 0 UTC 1 يناير 1970. |
| [Type](../../aspose.svg.dom.events/event/type) { get; } | اسم الحدث (غير حساس لحالة الأحرف). يجب أن يكون الاسم اسم XML . |
| [View](../../aspose.svg.events/timeevent/view) { get; } | تحدد سمة العرض AbstractView [DOM2VIEWS] الذي تم إنشاء الحدث منه. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [InitEvent](../../aspose.svg.dom.events/event/initevent)(string, bool, bool) | ملف[`InitEvent`](../../aspose.svg.dom.events/event/initevent) يتم استخدام طريقة لتهيئة قيمة[`Event`](../../aspose.svg.dom.events/event) تم إنشاؤه من خلال [`IDocumentEvent`](../../aspose.svg.dom.events/idocumentevent) الواجهة . |
| [InitTimeEvent](../../aspose.svg.events/timeevent/inittimeevent)(string, IAbstractView, long) | يتم استخدام أسلوب initTimeEvent لتهيئة قيمة حدث TimeEvent الذي تم إنشاؤه من خلال واجهة DocumentEvent. يمكن استدعاء هذه الطريقة فقط قبل إرسال TimeEvent عبر طريقة dispatchEvent ، على الرغم من أنه قد يتم استدعاؤها عدة مرات خلال تلك المرحلة إذا لزم الأمر. إذا تم استدعاؤه عدة مرات ، فإن الاستدعاء النهائي له الأسبقية. |
| [PreventDefault](../../aspose.svg.dom.events/event/preventdefault)() | إذا كان الحدث قابلاً للإلغاء ، فإن ملف[`PreventDefault`](../../aspose.svg.dom.events/event/preventdefault) يتم استخدام الطريقة للدلالة على أن الحدث سيتم إلغاؤه ، مما يعني أن أي إجراء افتراضي يتم اتخاذه عادةً بواسطة التنفيذ نتيجة للحدث لن يحدث. |
| [StopImmediatePropagation](../../aspose.svg.dom.events/event/stopimmediatepropagation)() | استدعاء هذه الطريقة يمنع الحدث من الوصول إلى أي مستمعين للأحداث مسجل بعد الحدث الحالي وعندما يتم إرساله في شجرة يمنع أيضًا الحدث من الوصول إلى أي كائنات أخرى. |
| [StopPropagation](../../aspose.svg.dom.events/event/stoppropagation)() | ملف[`StopPropagation`](../../aspose.svg.dom.events/event/stoppropagation) الطريقة المستخدمة لمنع المزيد من الانتشار لحدث ما أثناء تدفق الحدث. |

### أنظر أيضا

* class [Event](../../aspose.svg.dom.events/event)
* مساحة الاسم [Aspose.Svg.Events](../../aspose.svg.events)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
