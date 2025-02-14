---
title: PdfPermissions
second_title: Aspose.SVG لمرجع .NET API
description: يمثل هذا التعداد أذونات المستخدم لملف pdf.
type: docs
weight: 2890
url: /ar/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

يمثل هذا التعداد أذونات المستخدم لملف pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| PrintDocument | `4` | (معالجات الأمان للمراجعة 2) قم بطباعة المستند. (معالجات الأمان للمراجعة 3 أو أكبر) قم بطباعة المستند (ربما ليس بأعلى مستوى جودة ، اعتمادًا على ما إذا تم تعيين جودة الطباعة أيضًا) . |
| ModifyContent | `8` | تعديل محتويات المستند من خلال عمليات أخرى غير تلك التي يتم التحكم فيها بواسطة ModifyTextAnnotations و FillForm و 11. |
| ExtractContent | `10` | معالجات الأمان للمراجعة 2) نسخ أو استخراج النص والرسومات بطريقة أخرى من المستند ، بما في ذلك استخراج النص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الاحتياجات الخاصة أو لأغراض أخرى) . (معالجات الأمان للمراجعة 3 أو أكبر) نسخ أو استخرج النص والرسومات بطريقة أخرى من المستند من خلال عمليات أخرى غير تلك التي يتحكم فيها ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | قم بإضافة أو تعديل التعليقات التوضيحية النصية ، واملأ حقول النموذج التفاعلية ، وإذا تم أيضًا تعيين ModifyContent ، فقم بإنشاء أو تعديل حقول النموذج التفاعلية (بما في ذلك حقول التوقيع) . |
| FillForm | `100` | (معالجات الأمان للمراجعة 3 أو أكبر) املأ حقول النموذج التفاعلية الحالية (بما في ذلك حقول التوقيع) ، حتى إذا كان ModifyTextAnnotations واضحًا. |
| ExtractContentWithDisabilities | `200` | (معالجات الأمان للمراجعة 3 أو أكبر) استخراج النص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الاحتياجات الخاصة أو لأغراض أخرى) . |
| AssembleDocument | `400` | (معالجات الأمان للمراجعة 3 أو أكبر) قم بتجميع المستند (إدراج الصفحات أو تدويرها أو حذفها وإنشاء إشارات مرجعية أو صور مصغرة) ، حتى إذا كان تعديل المحتوى واضحًا. |
| PrintingQuality | `800` | (معالجات الأمان للمراجعة 3 أو أكبر) اطبع المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية موثوقة من محتوى PDF . عندما يكون هذا البت واضحًا (ويتم تعيين البت 3) ، تقتصر الطباعة على قيمة منخفضة - تمثيل بمستوى المظهر ، ربما بجودة متدهورة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
