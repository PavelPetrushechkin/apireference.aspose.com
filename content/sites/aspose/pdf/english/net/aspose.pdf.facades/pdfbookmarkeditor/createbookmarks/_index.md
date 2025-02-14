---
title: CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Creates bookmarks for all pages.
type: docs
weight: 30
url: /net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Creates bookmarks for all pages.

```csharp
public void CreateBookmarks()
```

### Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namespace [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | The bookmark will be added to the document. |

### Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bm1=new Bookmark();
bm1.PageNumber=1;
bm1.Title="First child";
Bookmark bm2=new Bookmark();
bm2.PageNumber=2;
bm2.Title="Second child";
Bookmark bm=new Bookmark();
bm.Action="GoTo";
bm.PageNumber=1;
bm.Title="Parent";
Bookmarks bms=new Bookmarks();
bms.Add(bm1);
bms.Add(bm2);
bm.ChildItem=bms;
editor.CreateBookmarks(bm);
editor.Save("example_out.pdf");
```

### See Also

* class [Bookmark](../../bookmark)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namespace [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Create bookmarks for all pages with specified color and style (bold, italic).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| color | Color | The color of title. |
| boldFlag | Boolean | The flag of bold attribution. |
| italicFlag | Boolean | The flag of italic attribution. |

### Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namespace [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
