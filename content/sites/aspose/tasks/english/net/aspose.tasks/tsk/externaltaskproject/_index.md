---
title: ExternalTaskProject
second_title: Aspose.Tasks for .NET API Reference
description: The source location and task identifier of an external task.
type: docs
weight: 380
url: /net/aspose.tasks/tsk/externaltaskproject/
---
## Tsk.ExternalTaskProject field

The source location and task identifier of an external task.

```csharp
public static readonly Key<string, TaskKey> ExternalTaskProject;
```

### Examples

Shows how to read/write Tsk.ExternalTaskProject property.

```csharp
var project = new Project();

var task = project.RootTask.Children.Add("Task");

task.Set(Tsk.ExternalTaskProject, "External Task");

Console.WriteLine("External Task Project: " + task.Get(Tsk.ExternalTaskProject));
```

### See Also

* struct [Key&lt;T,K&gt;](../../key-2)
* enum [TaskKey](../../taskkey)
* class [Tsk](../../tsk)
* namespace [Aspose.Tasks](../../tsk)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
