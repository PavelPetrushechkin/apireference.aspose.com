---
title: GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Returns the submit buttons submission flags
type: docs
weight: 260
url: /net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Returns the submit button's submission flags

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value

Submission flags of the button.

### Examples

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### See Also

* enum [SubmitFormFlag](../../submitformflag)
* class [Form](../../form)
* namespace [Aspose.Pdf.Facades](../../form)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
