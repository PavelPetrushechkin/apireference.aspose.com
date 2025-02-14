---
title: FinishDate
second_title: Aspose.Tasks for .NET API Reference
description: The finish date of a project.
type: docs
weight: 320
url: /net/aspose.tasks/prj/finishdate/
---
## Prj.FinishDate field

The finish date of a project.

```csharp
public static readonly Key<DateTime, PrjKey> FinishDate;
```

### Examples

Shows how to reschedule the project from finish date instead of the start one.

```csharp
var project = new Project();
project.Set(Prj.ScheduleFromStart, false);
project.Set(Prj.FinishDate, new DateTime(2020, 1, 1));

// Now all tasks dates (Start, Finish, EarlyStart, EarlyFinish, LateStart, LateFinish) are calculated. To get the critical path we need to calculate slacks (can be invoked in separate thread, but only after calculation of all early/late dates)
project.Recalculate();

foreach (var task in project.CriticalPath)
{
    Console.WriteLine(task.Get(Tsk.Id));
    Console.WriteLine(task.Get(Tsk.Name));
}
```

### See Also

* struct [Key&lt;T,K&gt;](../../key-2)
* enum [PrjKey](../../prjkey)
* class [Prj](../../prj)
* namespace [Aspose.Tasks](../../prj)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
