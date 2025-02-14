---
title: IWindow
second_title: Aspose.HTML لمرجع .NET API
description: يمثل كائن النافذة نافذة تحتوي على مستند DOM.
type: docs
weight: 4830
url: /ar/net/aspose.html.window/iwindow/
---
## IWindow interface

يمثل كائن النافذة نافذة تحتوي على مستند DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document) { get; } | يجب أن تقوم سمة المستند بإرجاع أحدث كائن مستند لكائن Window. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement) { get; } | كائن frameElement لمستند . |
| [Location](../../aspose.html.window/iwindow/location) { get; } | يجب أن تقوم سمة الموقع لواجهة Window بإرجاع كائن الموقع لمستند كائن النافذة هذا. |
| [Name](../../aspose.html.window/iwindow/name) { get; set; } | يجب أن تعيد سمة الاسم الخاصة بكائن Window ، عند الحصول عليها ، الاسم الحالي لسياق الاستعراض ، وعند الإعداد ، قم بتعيين اسم سياق الاستعراض على القيمة الجديدة. |
| [Opener](../../aspose.html.window/iwindow/opener) { get; } | سمة Opener IDL على كائن Window ، عند الحصول عليها ، يجب أن تعيد كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق تصفح الفتح الخاص به) ، إذا كان هناك واحد ، إذا كان لا يزال متاحًا ، وإذا سياق التصفح الحالي لم يتبرأ من افتتاحيته ؛ خلاف ذلك ، يجب أن ترجع فارغة. عند الإعداد ، إذا كانت القيمة الجديدة فارغة ، فيجب أن يتنكر سياق التصفح الحالي الافتتاحية الخاصة به ؛ إذا كانت القيمة الجديدة هي أي شيء آخر ، فيجب على وكيل المستخدم استدعاء الأسلوب الداخلي [[DefineOwnProperty]] لكائن Window ، وتمرير اسم الخاصية "opener" باعتباره مفتاح الخاصية ، وواصف الخاصية {[[القيمة]]: القيمة ، [[قابل للكتابة]]: صحيح ، [[Enumerable]]: صحيح ، [[قابل للتكوين]]: صحيح} باعتباره واصف الخاصية ، حيث تكون القيمة هي القيمة الجديدة. |
| [Parent](../../aspose.html.window/iwindow/parent) { get; } | يجب أن تُرجع سمة IDL الأصل على كائن Window لمستند في سياق استعراض b كائن WindowProxy لسياق التصفح الأصلي ، إذا كان هناك واحد (على سبيل المثال ، إذا كان b سياق تصفح فرعيًا) ، أو كائن WindowProxy في الاستعراض السياق ب نفسه ، بخلاف ذلك (على سبيل المثال ، إذا كان سياق تصفح عالي المستوى أو سياق تصفح متداخل منفصل) . |
| [Self](../../aspose.html.window/iwindow/self) { get; } | إرجاع كائن WindowProxy الخاص بسياق الاستعراض الخاص بكائن Window. |
| [Top](../../aspose.html.window/iwindow/top) { get; } | يجب أن تُرجع سمة IDL العلوية في كائن Window لمستند ما في سياق استعراض b كائن WindowProxy لسياق التصفح ذي المستوى الأعلى (والذي سيكون كائن WindowProxy الخاص به إذا كان سياق تصفح عالي المستوى بحد ذاته) ، إذا يحتوي على كائن WindowProxy واحد أو خاص به بخلاف ذلك (على سبيل المثال ، إذا كان سياق تصفح متداخلاً منفصلًا) . |
| [Window](../../aspose.html.window/iwindow/window) { get; } | إرجاع كائن WindowProxy الخاص بسياق الاستعراض الخاص بكائن Window. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert)(string) | يعرض تنبيهًا مشروطًا بالرسالة المحددة ، وينتظر حتى يقوم المستخدم بإغلاقها |
| [Confirm](../../aspose.html.window/iwindow/confirm)(string) | يعرض مطالبة موافق / إلغاء مشروط بالرسالة المحددة ، وينتظر أن يرفضها المستخدم ، ويعيد صحيحًا إذا نقر المستخدم على "موافق" و "خطأ" إذا نقر المستخدم فوق "إلغاء". |
| [Prompt](../../aspose.html.window/iwindow/prompt)(string, string) | يعرض موجه حقل نصي مع الرسالة المعينة ، وينتظر أن يقوم المستخدم برفضها ، ويعيد القيمة التي أدخلها المستخدم. إذا ألغى المستخدم الموجه ، فسيعيد القيمة فارغة بدلاً من ذلك. إذا كانت الوسيطة الثانية موجودة ، فسيتم استخدام القيمة المحددة كقيمة افتراضية. |

### أنظر أيضا

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers)
* interface [IWindowEventHandlers](../iwindoweventhandlers)
* interface [IWindowTimers](../iwindowtimers)
* مساحة الاسم [Aspose.Html.Window](../../aspose.html.window)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
