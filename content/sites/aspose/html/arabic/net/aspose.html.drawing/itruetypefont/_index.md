---
title: ITrueTypeFont
second_title: Aspose.HTML لمرجع .NET API
description: يعلن عن طرق للعمل مع خط TrueType .
type: docs
weight: 2750
url: /ar/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

يعلن عن طرق للعمل مع خط TrueType .

```csharp
public interface ITrueTypeFont
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize) { get; } | إرجاع حجم بيانات الخط بالبايت |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname) { get; } | احصل على اسم عائلة الخطوط . |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname) { get; } | يجب أن يكون هذا مزيجًا من "FamilyName" و "SubFamilyName". استثناء: إذا كان الخط "عادي" كما هو موضح في "SubFamilyName" ، فاستخدم اسم العائلة الموجود في "FamilyName" فقط. هناك استثناء للتعريف أعلاه لاسم الخط الكامل لسلاسل نظام Microsoft الأساسي لخطوط CFF OpenType: في هذه الحالة ، يجب أن تكون سلسلة اسم الخط الكامل مطابقة لـ PostScript FontName في اسم CFF INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname) { get; } | يميز اسم الفئة الفرعية للخط الخط في مجموعة لها نفس اسم عائلة الخط. من المفترض أن يعالج هذا النمط (مائل ، مائل) والوزن (خفيف ، غامق ، أسود ، إلخ). يجب أن يحتوي الخط الذي لا توجد به اختلافات معينة في الوزن أو النمط (مثل الوزن المتوسط ، وليس المائل ومجموعة بت 6 التحديد fs) على السلسلة "العادية" المخزنة في هذا الموضع. |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent)(float) | إرجاع الصعود بالنقاط. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata)() | افتح الدفق باستخدام بيانات الخط. المتصل مسؤول عن التخلص من الدفق. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent)(float) | إرجاع النسب بالنقاط. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Drawing](../../aspose.html.drawing)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
