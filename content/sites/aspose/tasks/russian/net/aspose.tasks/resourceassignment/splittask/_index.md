---
title: SplitTask
second_title: Справочник по Aspose.Tasks для .NET API
description: Разбивает задачу на две части.
type: docs
weight: 150
url: /ru/net/aspose.tasks/resourceassignment/splittask/
---
## ResourceAssignment.SplitTask method

Разбивает задачу на две части.

```csharp
public void SplitTask(DateTime start, DateTime finish, Calendar calendar)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| start | DateTime | Начало перерыва в работе разделить на основе. |
| finish | DateTime | Конец перерыва в работе разделить на основе. |
| calendar | Calendar | Календарь для разделения на основе. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Выдает, когда дата начала меньше даты начала назначения. |
| ArgumentOutOfRangeException | Генерируется, когда дата окончания больше, чем дата окончания задания. |

### Смотрите также

* class [Calendar](../../calendar)
* class [ResourceAssignment](../../resourceassignment)
* пространство имен [Aspose.Tasks](../../resourceassignment)
* сборка [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
