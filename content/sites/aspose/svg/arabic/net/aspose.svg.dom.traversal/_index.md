---
title: Aspose.Svg.Dom.Traversal
second_title: Aspose.SVG لمرجع .NET API
description: ملف Aspose.Svg دوم ترافيرساليحتوي مساحة الاسم على الأساليب التي إنشاء مكررات وممرات شجرية للتنقل بين العناصر و اجتياز عقدة وأفرادها بترتيب المستند.
type: docs
weight: 100
url: /ar/net/aspose.svg.dom.traversal/
---
ملف **Aspose.Svg دوم ترافيرسال**يحتوي مساحة الاسم على الأساليب التي إنشاء مكررات وممرات شجرية للتنقل بين العناصر و اجتياز عقدة وأفرادها بترتيب المستند.

## واجهات

| واجهه المستخدم | وصف |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal) | يحتوي DocumentTraversal على طرق تنشئ مكررات و مشي شجرة لاجتياز عقدة وتوابعها بترتيب المستند (العمق أولاً ، اجتياز الطلب المسبق ، وهو ما يعادل الترتيب الذي تظهر به علامات البدء في التمثيل النصي لـ المستند). في DOMs التي تدعم ميزة الاجتياز ، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تنفذ واجهة المستند. |
| [IElementTraversal](./ielementtraversal) | واجهة ElementTraversal هي مجموعة من سمات القراءة فقط التي تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في توافق عمليات تنفيذ Element Traversal ، يجب على جميع الكائنات التي تنفذ Element أيضًا تنفيذ واجهة ElementTraversal . |
| [INodeFilter](./inodefilter) | المرشحات هي كائنات تعرف كيفية "تصفية" العقد. إذا تم إعطاء NodeIterator أو TreeWalker NodeFilter ، فإنه يطبق عامل التصفية قبل إرجاع العقدة التالية . إذا طلب عامل التصفية قبول العقدة ، فسيعيد منطق الاجتياز it؛ وبخلاف ذلك ، يبحث الاجتياز عن العقدة التالية ويتظاهر بأن العقدة التي تم رفضها لم تكن موجودة. |
| [INodeIterator](./inodeiterator) | يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () . |
| [ITraversal](./itraversal) | يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () . |
| [ITreeWalker](./itreewalker) | يتم استخدام كائنات TreeWalker للتنقل في شجرة مستند أو شجرة فرعية باستخدام طريقة عرض المستند المحددة بواسطة علامات ومرشحات whatToShow الخاصة بهم (إن وجدت). أي وظيفة تؤدي إلى التنقل باستخدام TreeWalker ستدعم تلقائيًا أي طريقة عرض محددة بواسطة TreeWalker. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
