---
title: ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Exports the content of the fields of the pdf into the xml stream. The button fields value will not be exported.
type: docs
weight: 80
url: /net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputXfdfStream | Stream | The output xml stream. |

### Examples

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### See Also

* class [Form](../../form)
* namespace [Aspose.Pdf.Facades](../../form)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
