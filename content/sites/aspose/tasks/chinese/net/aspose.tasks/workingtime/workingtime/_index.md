---
title: WorkingTime
second_title: Aspose.Tasks for .NET API 参考
description: 初始化WorkingTimeaspose.tasks/workingtime具有指定开始和结束时间间隔的类
type: docs
weight: 10
url: /zh/net/aspose.tasks/workingtime/workingtime/
---
## WorkingTime(DateTime, DateTime) {#constructor_2}

初始化[`WorkingTime`](../../workingtime)具有指定开始和结束时间间隔的类。

```csharp
public WorkingTime(DateTime fromTime, DateTime toTime)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fromTime | DateTime | 间隔开始时间 |
| toTime | DateTime | 间隔结束时间 |

### 也可以看看

* class [WorkingTime](../../workingtime)
* 命名空间 [Aspose.Tasks](../../workingtime)
* 部件 [Aspose.Tasks](../../../)

---

## WorkingTime(TimeSpan, TimeSpan) {#constructor_3}

初始化[`WorkingTime`](../../workingtime)具有指定开始和结束时间的间隔项的类。

```csharp
public WorkingTime(TimeSpan fromTime, TimeSpan toTime)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fromTime | TimeSpan | 间隔的开始时间由TimeSpan结构。 |
| toTime | TimeSpan | 区间的结束时间由TimeSpan结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 当 toTime 小于等于 toTime 参数 或当 fromTime 和 toTime 之间的间隔大于 24 小时时。 |

### 例子

WorkingTime ctor 的重载可用于使用 TimeSpan 初始化间隔的开始和结束：

```csharp
[C#]
var wt = new WorkingTime(new TimeSpan(9, 0, 0), new TimeSpan(18, 0, 0));
```

### 也可以看看

* class [WorkingTime](../../workingtime)
* 命名空间 [Aspose.Tasks](../../workingtime)
* 部件 [Aspose.Tasks](../../../)

---

## WorkingTime(int, int) {#constructor_1}

初始化[`WorkingTime`](../../workingtime)具有指定开始和结束时间的间隔项的类。

```csharp
public WorkingTime(int fromHours, int toHours)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fromHours | Int32 | 以整数小时数 (0-24) 表示的时间间隔的开始时间。 |
| toHours | Int32 | 间隔的结束时间，以整数小时数 (0-24) 表示。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 当 toTime 小于等于 toTime 参数 或当 fromTime 和 toTime 之间的间隔大于 24 小时时。 |

### 例子

WorkingTime ctor 的重载可用于使用整小时初始化间隔的开始和结束：

```csharp
[C#]
var wt = new WorkingTime(9, 13);
```

### 也可以看看

* class [WorkingTime](../../workingtime)
* 命名空间 [Aspose.Tasks](../../workingtime)
* 部件 [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
