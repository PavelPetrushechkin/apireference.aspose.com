---
title: EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Encrypts Pdf file with userpassword and ownerpassword and sets the documents privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed.
type: docs
weight: 70
url: /net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privilege | DocumentPrivilege | Set privilege. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

### Return Value

True for success.

### Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* namespace [Aspose.Pdf.Facades](../../pdffilesecurity)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privilege | DocumentPrivilege | Set privilege. |
| keySize | KeySize | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |
| cipher | Algorithm | Algorithm.AES to encrypt using AES algorithm or Algorithm.RC4 for RC4 encryption. |

### Return Value

True for success.

### Examples

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### See Also

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* namespace [Aspose.Pdf.Facades](../../pdffilesecurity)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
