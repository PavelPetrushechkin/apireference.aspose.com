---
title: SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.
type: docs
weight: 80
url: /net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value

True for success.

### Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* namespace [Aspose.Pdf.Facades](../../pdffilesecurity)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Sets Pdf file security with original password. Throws an exception if process failed.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | Original user password. |
| ownerPassword | String | Original owner password. |
| privilege | DocumentPrivilege | Set privilege. |

### Return Value

True for success.

### Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege)
* class [PdfFileSecurity](../../pdffilesecurity)
* namespace [Aspose.Pdf.Facades](../../pdffilesecurity)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
