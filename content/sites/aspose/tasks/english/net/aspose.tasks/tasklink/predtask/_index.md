---
title: PredTask
second_title: Aspose.Tasks for .NET API Reference
description: Gets or sets the predecessor task.
type: docs
weight: 60
url: /net/aspose.tasks/tasklink/predtask/
---
## TaskLink.PredTask property

Gets or sets the predecessor task.

```csharp
public Task PredTask { get; set; }
```

### Examples

Shows how to read project task links.

```csharp
var project = new Project(DataDir + "GetPredecessorSuccessorTasks.mpp");

// Display names of predecessor and successor tasks
foreach (var taskLink in project.TaskLinks)
{
    Console.WriteLine("Predecessor: " + taskLink.PredTask.Get(Tsk.Name));
    Console.WriteLine("Successor: " + taskLink.SuccTask.Get(Tsk.Name));
    Console.WriteLine("Lag Format: " + taskLink.LagFormat);
    Console.WriteLine("Link Lag: " + taskLink.LinkLag);
    Console.WriteLine();
}
```

### See Also

* class [Task](../../task)
* class [TaskLink](../../tasklink)
* namespace [Aspose.Tasks](../../tasklink)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
