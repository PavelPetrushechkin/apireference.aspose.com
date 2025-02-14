---
title: ParentProject
second_title: Aspose.Tasks for .NET API Reference
description: Gets a parent Projectaspose.tasks/project of this object.
type: docs
weight: 20
url: /net/aspose.tasks/calendarcollection/parentproject/
---
## CalendarCollection.ParentProject property

Gets a parent [`Project`](../../project) of this object.

```csharp
public Project ParentProject { get; }
```

### Examples

Shows how to read calendar parent project properties.

```csharp
var project = new Project(DataDir + "Project5.mpp");

var calendarByName = project.Calendars.GetByName("TestCalendar");

Console.WriteLine("Calendar Name: " + calendarByName.ParentProject.Get(Prj.Name));
```

### See Also

* class [Project](../../project)
* class [CalendarCollection](../../calendarcollection)
* namespace [Aspose.Tasks](../../calendarcollection)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
