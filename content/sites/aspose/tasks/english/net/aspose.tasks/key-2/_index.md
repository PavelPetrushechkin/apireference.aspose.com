---
title: KeyTK
second_title: Aspose.Tasks for .NET API Reference
description: Represents a property key of a class of the specified type. An instance of this class is used when getting or setting property of a container.
type: docs
weight: 840
url: /net/aspose.tasks/key-2/
---
## Key&lt;T,K&gt; structure

Represents a property key of a class of the specified type. An instance of this class is used when getting or setting property of a container.

```csharp
public struct Key<T, K>
    where K : struct
```

| Parameter | Description |
| --- | --- |
| T | The type of property value. |
| K | The type of property key. |

## Properties

| Name | Description |
| --- | --- |
| [KeyType](../../aspose.tasks/key`2/keytype) { get; } |  |

### Examples

Shows how to read/write Prj.ActualsInSync property.

```csharp
var project = new Project();

project.Set(Prj.ActualsInSync, true);

Console.WriteLine("Actuals In Sync: " + project.Get(Prj.ActualsInSync));
```

### See Also

* namespace [Aspose.Tasks](../../aspose.tasks)
* assembly [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
