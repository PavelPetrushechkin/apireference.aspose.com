---
title: Resource
second_title: Aspose.Tasks for .NET API 参考
description: 表示项目中的资源
type: docs
weight: 1480
url: /zh/net/aspose.tasks/resource/
---
## Resource class

表示项目中的资源。

```csharp
public class Resource : IEquatable<Resource>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Assignments](../../aspose.tasks/resource/assignments) { get; } | 获取此对象的资源分配集合。 |
| [AvailabilityPeriods](../../aspose.tasks/resource/availabilityperiods) { get; } | 获取一个实例[`AvailabilityPeriodCollection`](../availabilityperiodcollection)class. 资源可用期间的集合。 |
| [Baselines](../../aspose.tasks/resource/baselines) { get; } | 获取此对象的 BaselineCollection 实例。 资源的基线值。 |
| [ExtendedAttributes](../../aspose.tasks/resource/extendedattributes) { get; } | 获取扩展属性的值。 |
| virtual [IsRoot](../../aspose.tasks/resource/isroot) { get; } | 获取指示资源是否为根资源的标志。 根资源是一种特殊资源，旨在支持 MS Project 格式的内部结构，不打算直接从用户代码中使用。 |
| [OutlineCode](../../aspose.tasks/resource/outlinecode) { get; } | 获取 OutlineCodeCollection 对象。 大纲代码的值。 |
| [ParentProject](../../aspose.tasks/resource/parentproject) { get; } | 获取此容器的父项目。 |
| [Rates](../../aspose.tasks/resource/rates) { get; } | 获取一个实例[`RateCollection`](../ratecollection)此对象的类。 与每个相关的周期和费率的集合。 |
| [TimephasedData](../../aspose.tasks/resource/timephaseddata) { get; set; } | 获取或设置的实例[`TimephasedDataCollection`](../timephaseddatacollection)此对象的类。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Delete](../../aspose.tasks/resource/delete)() | 从项目中删除资源及其分配。 |
| override [Equals](../../aspose.tasks/resource/equals#equals_1)(object) | 返回一个值，指示此实例是否等于指定对象。 |
| [Equals](../../aspose.tasks/resource/equals#equals)(Resource) | 返回一个值，该值指示此实例是否等于[`Resource`](../resource)类. |
| [Get&lt;T&gt;](../../aspose.tasks/resource/get)(Key&lt;T, RscKey&gt;) | 返回此容器中属性映射到的值。 |
| override [GetHashCode](../../aspose.tasks/resource/gethashcode)() | 返回实例的哈希码值[`Resource`](../resource)类. |
| [GetTimephasedData](../../aspose.tasks/resource/gettimephaseddata#gettimephaseddata)(DateTime, DateTime) | 返回[`TimephasedDataCollection`](../timephaseddatacollection)对于这个对象[`TimephasedData`](./timephaseddata)给定开始日期和结束日期内的值。 |
| [GetTimephasedData](../../aspose.tasks/resource/gettimephaseddata#gettimephaseddata_1)(DateTime, DateTime, TimephasedDataType) | 返回一个实例[`TimephasedDataCollection`](../timephaseddatacollection)此对象的类与[`TimephasedData`](./timephaseddata)指定的给定开始和结束日期内的值[`TimephasedDataType`](../timephaseddatatype). |
| [Set](../../aspose.tasks/resource/set#set)(Key&lt;DateTime, RscKey&gt;, DateTime) | 将指定属性映射到此容器中的指定值。 |
| [Set&lt;T&gt;](../../aspose.tasks/resource/set#set_1)(Key&lt;T, RscKey&gt;, T) | 将指定属性映射到此容器中的指定值。 |
| override [ToString](../../aspose.tasks/resource/tostring)() | 返回实例的短字符串表示[`Resource`](../resource)class. 表示的确切细节未指定，可能会发生变化。 |

### 也可以看看

* 命名空间 [Aspose.Tasks](../../aspose.tasks)
* 部件 [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
