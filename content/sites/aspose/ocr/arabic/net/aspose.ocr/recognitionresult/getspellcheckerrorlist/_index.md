---
title: GetSpellCheckErrorList
second_title: Aspose.OCR لمرجع .NET API
description: ابحث عن الكلمات التي بها أخطاء إملائية مع التهجئات المقترحة لنص إدخال معين.
type: docs
weight: 100
url: /ar/net/aspose.ocr/recognitionresult/getspellcheckerrorlist/
---
## RecognitionResult.GetSpellCheckErrorList method

ابحث عن الكلمات التي بها أخطاء إملائية مع التهجئات المقترحة لنص إدخال معين.

```csharp
public List<SpellCheckError> GetSpellCheckErrorList(
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| language | SpellCheckLanguage | القاموس المراد استخدامه. |
| dictionaryPath | String | اختياريا. المسار الكامل إلى قاموس المستخدم (قاموس التردد). تنسيق ملف القاموس: ملف نصي عادي بترميز UTF-8. يتم الفصل بين تردد الكلمات والكلمة بمسافة أو علامة تبويب ، ويُتوقع أن تكون الكلمة في العمود الأول والتردد في العمود الثاني. زوج التردد في سطر منفصل. يتم تعريف السطر على أنه تسلسل من الأحرف متبوعًا بتغذية سطر ("\ n") ، أو حرف إرجاع ("\ r") ، أو أو حرف إرجاع متبوعًا مباشرة بخط تغذية ("\ r \ n") . من المتوقع أن تكون كل كلمة بأحرف صغيرة . |

### قيمة الإرجاع

اقترحت قائمة بكائن SpellCheckError الكلمات التي بها أخطاء إملائية مع القوائم هجاءًا صحيحًا لكل كلمة بها أخطاء إملائية ، ومع مسافة التحرير.

### أنظر أيضا

* struct [SpellCheckError](../../../aspose.ocr.spellchecker/spellcheckerror)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* مساحة الاسم [Aspose.OCR](../../recognitionresult)
* المجسم [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
