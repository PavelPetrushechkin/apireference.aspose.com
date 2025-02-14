---
title: RemoveEventListener
second_title: Aspose.HTML لمرجع .NET API
description: تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كانIEventListeneraspose.html.dom.events/ieventlistener تمت إزالته من ملفEventTargetaspose.html.dom/eventtarget أثناء معالجة حدث  لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.
type: docs
weight: 30
url: /ar/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../ieventlistener) تمت إزالته من ملف[`EventTarget`](../../../aspose.html.dom/eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | يحدد نوع حدث[`IEventListener`](../../ieventlistener) يتم إزالتها. |
| listener | IEventListener | ال[`IEventListener`](../../ieventlistener) تشير المعلمة إلى[`IEventListener`](../../ieventlistener) ليتم إزالتها. |

### أنظر أيضا

* interface [IEventListener](../../ieventlistener)
* interface [IEventTarget](../../ieventtarget)
* مساحة الاسم [Aspose.Html.Dom.Events](../../ieventtarget)
* المجسم [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../ieventlistener) تمت إزالته من ملف[`EventTarget`](../../../aspose.html.dom/eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | String | يحدد نوع حدث[`IEventListener`](../../ieventlistener) يتم إزالتها. |
| listener | IEventListener | ال[`IEventListener`](../../ieventlistener) تشير المعلمة إلى[`IEventListener`](../../ieventlistener) ليتم إزالتها. |
| useCapture | Boolean | يحدد ما إذا كان EventListener الذي يتم إزالته مسجلاً كمستمع ملتقط أم لا. من نفس المستمع والعكس صحيح. |

### أنظر أيضا

* interface [IEventListener](../../ieventlistener)
* interface [IEventTarget](../../ieventtarget)
* مساحة الاسم [Aspose.Html.Dom.Events](../../ieventtarget)
* المجسم [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
