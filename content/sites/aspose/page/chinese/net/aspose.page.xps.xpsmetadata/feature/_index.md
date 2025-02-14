---
title: Feature
second_title: Aspose.Page for .NET API 参考
description: 封装通用打印模式特征的类 所有模式定义特征的基类 A元素包含完整的列表Option./option和Property./property 完全描述设备属性作业格式设置或其他相关特征的元素 https//docs.microsoft.com/enus/windows/win32/printdocs/feature
type: docs
weight: 810
url: /zh/net/aspose.page.xps.xpsmetadata/feature/
---
## Feature class

封装通用打印模式特征的类。 所有模式定义特征的基类。 A元素包含完整的列表[`Option`](../option)和[`Property`](../property) 完全描述设备属性、作业格式设置或其他相关特征的元素。 https://docs.microsoft.com/en-us/windows/win32/printdocs/feature

```csharp
Feature
```

```csharp
public class Feature : CompositePrintTicketElement, IFeatureItem, IPrintTicketItem
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Feature](feature#constructor)(string, Feature, params IFeatureItem[]) | 创建一个新的 PrintTicket 功能实例。 |
| [Feature](feature#constructor_1)(string, Option, params IFeatureItem[]) | 创建一个新的 PrintTicket 功能实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Name](../../aspose.page.xps.xpsmetadata/printticketelement/name) { get; } | 获取元素名称。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.page.xps.xpsmetadata/feature/add)(params IFeatureItem[]) | 将项目列表添加到此功能项目列表的末尾。 每一个都必须是一个[`Feature`](../feature)， 一个[`Option`](../option)或一个[`Property`](../property)实例. |

### 也可以看看

* class [CompositePrintTicketElement](../compositeprintticketelement)
* interface [IFeatureItem](../ifeatureitem)
* interface [IPrintTicketItem](../iprintticketitem)
* 命名空间 [Aspose.Page.XPS.XpsMetadata](../../aspose.page.xps.xpsmetadata)
* 部件 [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
