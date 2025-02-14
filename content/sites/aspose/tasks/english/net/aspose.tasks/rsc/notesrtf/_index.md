---
title: NotesRTF
second_title: Aspose.Tasks for .NET API Reference
description: The text notes in RTF format. Supported for MPP formats only. String type.
type: docs
weight: 480
url: /net/aspose.tasks/rsc/notesrtf/
---
## Rsc.NotesRTF field

The text notes in RTF format. Supported for MPP formats only. String type.

```csharp
public static readonly Key<string, RscKey> NotesRTF;
```

### Examples

Shows how to read/write Rsc.NotesRTF property.

```csharp
var project = new Project();

            var resource = project.Resources.Add("Resource");

            const string RTF = @"{\rtf1\ansi\ansicpg1252\deff0\deflang1033{\fonttbl{\f0\fnil\fcharset134 SimSun;}{\f1\fnil\fcharset0 Calibri;}}
{\*\generator Msftedit 5.41.21.2510;}\viewkind4\uc1\pard\sa200\sl276\slmult1\lang9\f0\fs22\'d4\'e7\'c9\'cf\'ba\'c3\f1\par
}
 "; // 早上好

            resource.Set(Rsc.NotesRTF, RTF);

            Console.WriteLine("Notes R T F: " + resource.Get(Rsc.NotesRTF));
```

### See Also

* struct [Key&lt;T,K&gt;](../../key-2)
* enum [RscKey](../../rsckey)
* class [Rsc](../../rsc)
* namespace [Aspose.Tasks](../../rsc)
* assembly [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
