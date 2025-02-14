---
title: TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Initializes a new instance of the TextAbsorberaspose.pdf.text/textabsorber.
type: docs
weight: 10
url: /net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Initializes a new instance of the [`TextAbsorber`](../../textabsorber).

```csharp
public TextAbsorber()
```

### Remarks

Performs text extraction and provides access to the extracted text via [`Text`](../text) object.

### Examples

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextAbsorber](../../textabsorber)
* namespace [Aspose.Pdf.Text](../../textabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initializes a new instance of the [`TextAbsorber`](../../textabsorber) with extraction options.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |

### Remarks

Performs text extraction and provides access to the extracted text via [`Text`](../text) object.

### Examples

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextExtractionOptions](../../textextractionoptions)
* class [TextAbsorber](../../textabsorber)
* namespace [Aspose.Pdf.Text](../../textabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initializes a new instance of the [`TextAbsorber`](../../textabsorber) with extraction and text search options.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |
| textSearchOptions | TextSearchOptions | Text search options |

### Remarks

Performs text extraction and provides access to the extracted text via [`Text`](../text) object.

### See Also

* class [TextExtractionOptions](../../textextractionoptions)
* class [TextSearchOptions](../../textsearchoptions)
* class [TextAbsorber](../../textabsorber)
* namespace [Aspose.Pdf.Text](../../textabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initializes a new instance of the [`TextAbsorber`](../../textabsorber) with text search options.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Text search options |

### Remarks

Performs text extraction and provides access to the extracted text via [`Text`](../text) object.

### See Also

* class [TextSearchOptions](../../textsearchoptions)
* class [TextAbsorber](../../textabsorber)
* namespace [Aspose.Pdf.Text](../../textabsorber)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
