---
title: Clone
second_title: Aspose.Tasks for .NET API Reference
description: Creates full copy of a task without subtasks.
type: docs
weight: 130
url: /net/aspose.tasks/task/clone/
---
## Task.Clone method

Creates full copy of a task without subtasks.

```csharp
public object Clone()
```

### Return Value

Created copy of a task.

### Examples

Shows how to clone a task.

```csharp
var project = new Project();

var originalTask = project.RootTask.Children.Add("Task");
var cloneTask = (Task)originalTask.Clone();

Console.WriteLine("Are tasks equal: " + cloneTask.Equals(originalTask));
```

### See Also

* class [Task](../../task)
* namespace [Aspose.Tasks](../../task)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
