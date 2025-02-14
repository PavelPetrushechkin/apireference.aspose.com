---
title: CreateLookupTaskDefinition
second_title: Aspose.Tasks لمرجع .NET API
description: طريقة المصنع التي تنشئ تعريف سمة موسع مع البحث. لديهاCalculationTypeaspose.tasks/extendedattributedefinition/calculationtype يساويLookup ويمكن استخدامها في المهام فقط. أنت مطالب بالتحديدfieldId وalias عند استدعاء هذه الطريقة. يتم استنتاج نوع الحقل من معرف الحقل.
type: docs
weight: 20
url: /ar/net/aspose.tasks/extendedattributedefinition/createlookuptaskdefinition/
---
## CreateLookupTaskDefinition(ExtendedAttributeTask, string) {#createlookuptaskdefinition_1}

طريقة المصنع التي تنشئ تعريف سمة موسع مع البحث. لديها[`CalculationType`](../calculationtype) يساويLookup ويمكن استخدامها في المهام فقط. أنت مطالب بالتحديد*fieldId* و*alias* عند استدعاء هذه الطريقة. يتم استنتاج نوع الحقل من معرف الحقل.

```csharp
public static ExtendedAttributeDefinition CreateLookupTaskDefinition(ExtendedAttributeTask fieldId, 
    string alias)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldId | ExtendedAttributeTask | المحدد[`ExtendedAttributeTask`](../../extendedattributetask) معرف المجال. |
| alias | String | المحددString الاسم المستعار. |

### قيمة الإرجاع

تم إنشاء مثيل لـ[`ExtendedAttributeDefinition`](../../extendedattributedefinition) فئة مع المحدد*fieldId* و*alias*.

### أمثلة

استخدم هذا المثال لإنشاء تعريف حقل مخصص لمهمة مع البحث ثم قم بتعبئته بقيم نصية:

```csharp
var taskTextAttr = ExtendedAttributeDefinition.CreateLookupTaskDefinition(ExtendedAttributeTask.Text27, "My custom field");
taskTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
taskTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(taskTextAttr);
```

### أنظر أيضا

* enum [ExtendedAttributeTask](../../extendedattributetask)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* مساحة الاسم [Aspose.Tasks](../../extendedattributedefinition)
* المجسم [Aspose.Tasks](../../../)

---

## CreateLookupTaskDefinition(CustomFieldType, ExtendedAttributeTask, string) {#createlookuptaskdefinition}

طريقة المصنع التي تنشئ تعريف سمة موسع مع البحث. لديها[`CalculationType`](../calculationtype) يساويLookup ويمكن استخدامها في المهام فقط. أنت مطالب بالتحديد*customFieldType* و*fieldId* و*alias* عند استدعاء هذه الطريقة.

```csharp
public static ExtendedAttributeDefinition CreateLookupTaskDefinition(
    CustomFieldType customFieldType, ExtendedAttributeTask fieldId, string alias)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| customFieldType | CustomFieldType | المحدد[`CustomFieldType`](../../customfieldtype) يكتب. |
| fieldId | ExtendedAttributeTask | المحدد[`ExtendedAttributeTask`](../../extendedattributetask) معرف المجال. |
| alias | String | المحددString الاسم المستعار. |

### قيمة الإرجاع

تم إنشاء مثيل لـ[`ExtendedAttributeDefinition`](../../extendedattributedefinition) فئة مع المحدد*customFieldType* و*fieldId* و*alias*.

### أمثلة

استخدم هذا المثال لإنشاء تعريف حقل مخصص لمهمة مع البحث ثم قم بتعبئته بقيم نصية:

```csharp
var taskTextAttr = ExtendedAttributeDefinition.CreateLookupTaskDefinition(CustomFieldType.Text, ExtendedAttributeTask.Text27, "My custom field");
taskTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
taskTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(taskTextAttr);
```

### أنظر أيضا

* enum [CustomFieldType](../../customfieldtype)
* enum [ExtendedAttributeTask](../../extendedattributetask)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* مساحة الاسم [Aspose.Tasks](../../extendedattributedefinition)
* المجسم [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
