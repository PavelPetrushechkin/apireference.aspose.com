---
title: Work
second_title: Aspose.Tasks for .NET API Reference
description: The total amount of time scheduled for a resource on a task.
type: docs
weight: 700
url: /net/aspose.tasks/rsc/work/
---
## Rsc.Work field

The total amount of time scheduled for a resource on a task.

```csharp
public static readonly Key<Duration, RscKey> Work;
```

### Examples

Shows how to read/write Rsc.Work property.

```csharp
var project = new Project();
project.Set(Prj.WorkFormat, TimeUnitType.Day);

var resource = project.Resources.Add("Resource");

resource.Set(Rsc.Work, project.GetWork(1));

Console.WriteLine("Work: " + resource.Get(Rsc.Work));
```

### See Also

* struct [Key&lt;T,K&gt;](../../key-2)
* struct [Duration](../../duration)
* enum [RscKey](../../rsckey)
* class [Rsc](../../rsc)
* namespace [Aspose.Tasks](../../rsc)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
