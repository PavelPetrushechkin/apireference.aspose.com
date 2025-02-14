---
title: CreateLookupTaskDefinition
second_title: Aspose.Tasks for .NET API 参考
description: 使用查找创建扩展属性定义的工厂方法 它有CalculationTypeaspose.tasks/extendedattributedefinition/calculationtype等于Lookup并且只能在任务中使用 您需要指定fieldId和alias调用此方法时 字段类型由字段id推断
type: docs
weight: 20
url: /zh/net/aspose.tasks/extendedattributedefinition/createlookuptaskdefinition/
---
## CreateLookupTaskDefinition(ExtendedAttributeTask, string) {#createlookuptaskdefinition_1}

使用查找创建扩展属性定义的工厂方法。 它有[`CalculationType`](../calculationtype)等于Lookup并且只能在任务中使用。 您需要指定*fieldId*和*alias*调用此方法时。 字段类型由字段id推断。

```csharp
public static ExtendedAttributeDefinition CreateLookupTaskDefinition(ExtendedAttributeTask fieldId, 
    string alias)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldId | ExtendedAttributeTask | 指定的[`ExtendedAttributeTask`](../../extendedattributetask)字段标识。 |
| alias | String | 指定的String别名。 |

### 返回值

创建的实例[`ExtendedAttributeDefinition`](../../extendedattributedefinition)指定的类*fieldId*和*alias*.

### 例子

使用此示例为具有查找的任务创建自定义字段定义，然后用文本值填充它：

```csharp
var taskTextAttr = ExtendedAttributeDefinition.CreateLookupTaskDefinition(ExtendedAttributeTask.Text27, "My custom field");
taskTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
taskTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(taskTextAttr);
```

### 也可以看看

* enum [ExtendedAttributeTask](../../extendedattributetask)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* 命名空间 [Aspose.Tasks](../../extendedattributedefinition)
* 部件 [Aspose.Tasks](../../../)

---

## CreateLookupTaskDefinition(CustomFieldType, ExtendedAttributeTask, string) {#createlookuptaskdefinition}

使用查找创建扩展属性定义的工厂方法。 它有[`CalculationType`](../calculationtype)等于Lookup并且只能在任务中使用。 您需要指定*customFieldType* ,*fieldId*和*alias*调用此方法时。

```csharp
public static ExtendedAttributeDefinition CreateLookupTaskDefinition(
    CustomFieldType customFieldType, ExtendedAttributeTask fieldId, string alias)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customFieldType | CustomFieldType | 指定的[`CustomFieldType`](../../customfieldtype)类型。 |
| fieldId | ExtendedAttributeTask | 指定的[`ExtendedAttributeTask`](../../extendedattributetask)字段标识。 |
| alias | String | 指定的String别名。 |

### 返回值

创建的实例[`ExtendedAttributeDefinition`](../../extendedattributedefinition)指定的类*customFieldType* ,*fieldId*和*alias*.

### 例子

使用此示例为具有查找的任务创建自定义字段定义，然后用文本值填充它：

```csharp
var taskTextAttr = ExtendedAttributeDefinition.CreateLookupTaskDefinition(CustomFieldType.Text, ExtendedAttributeTask.Text27, "My custom field");
taskTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
taskTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(taskTextAttr);
```

### 也可以看看

* enum [CustomFieldType](../../customfieldtype)
* enum [ExtendedAttributeTask](../../extendedattributetask)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* 命名空间 [Aspose.Tasks](../../extendedattributedefinition)
* 部件 [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
