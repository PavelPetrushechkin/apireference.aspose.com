---
title: Save
second_title: Aspose.Sildes for .NET API Reference
description: Saves the output file to the given path.
type: docs
weight: 10
url: /net/aspose.slides.export.web/ioutputsaver/save/
---
## IOutputSaver.Save method

Saves the output file to the given path.

```csharp
public void Save(string path, IOutputFile outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Path to save the file to. |
| outputFile | IOutputFile | Output file. |

### Examples

Saving into the FileStream implementation example:

```csharp
[C#]
public void Save(string path, IOutputFile outputFile)
{
    using (FileStream stream = new FileStream(path, FileMode.Create))
    {
        outputFile.Write(stream);
    }
}
```

### See Also

* interface [IOutputFile](../../ioutputfile)
* interface [IOutputSaver](../../ioutputsaver)
* namespace [Aspose.Slides.Export.Web](../../ioutputsaver)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
