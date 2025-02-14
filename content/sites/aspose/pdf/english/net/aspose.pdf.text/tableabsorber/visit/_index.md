---
title: Visit
second_title: Aspose.PDF for .NET API Reference
description: Extracts tables on the specified page
type: docs
weight: 70
url: /net/aspose.pdf.text/tableabsorber/visit/
---
## TableAbsorber.Visit method

Extracts tables on the specified page

```csharp
public virtual void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | Pdf pocument page object. |

### Examples

The example demonstrates how to extract table on the first PDF document page.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [Page](../../../aspose.pdf/page)
* class [TableAbsorber](../../tableabsorber)
* namespace [Aspose.Pdf.Text](../../tableabsorber)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
