---
title: CreateWorkTimephased
second_title: Aspose.Tasks for .NET API 参考
description: 创建并初始化TimephasedDataaspose.tasks/timephaseddata基于工作的时间阶段数据的类
type: docs
weight: 40
url: /zh/net/aspose.tasks/timephaseddata/createworktimephased/
---
## TimephasedData.CreateWorkTimephased method

创建并初始化[`TimephasedData`](../../timephaseddata)基于工作的时间阶段数据的类。

```csharp
public static TimephasedData CreateWorkTimephased(int uid, DateTime start, DateTime finish, 
    TimeSpan value, TimeUnitType timeUnit, TimephasedDataType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| uid | Int32 | 任务的 UID。 |
| start | DateTime | 开始日期时间。 |
| finish | DateTime | 完成日期时间。 |
| value | TimeSpan | 时间跨度值。 |
| timeUnit | TimeUnitType | 时间单位类型。 |
| type | TimephasedDataType | 时间分段数据类型。 |

### 返回值

的一个实例[`TimephasedData`](../../timephaseddata)基于工作的时间阶段数据的类。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 如果指定了负工作值。 |

### 也可以看看

* enum [TimeUnitType](../../timeunittype)
* enum [TimephasedDataType](../../timephaseddatatype)
* class [TimephasedData](../../timephaseddata)
* 命名空间 [Aspose.Tasks](../../timephaseddata)
* 部件 [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
