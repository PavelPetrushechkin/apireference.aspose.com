---
title: DigitalSignatureCollection
second_title: Aspose.Cells for .NET API Reference
description: Provides a collection of digital signatures attached to a document.
type: docs
weight: 1410
url: /net/aspose.cells.digitalsignatures/digitalsignaturecollection/
---
## DigitalSignatureCollection class

Provides a collection of digital signatures attached to a document.

```csharp
public class DigitalSignatureCollection : IEnumerable
```

## Constructors

| Name | Description |
| --- | --- |
| [DigitalSignatureCollection](digitalsignaturecollection)() | The constructor of DigitalSignatureCollection. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.cells.digitalsignatures/digitalsignaturecollection/add)(DigitalSignature) | Add one signature to DigitalSignatureCollection. |
| [GetEnumerator](../../aspose.cells.digitalsignatures/digitalsignaturecollection/getenumerator)() | Get the enumerator for DigitalSignatureCollection, this enumerator allows iteration over the collection |

### Examples

The following example shows how to create digital signature

```csharp
[C#]
internal void ValidateSignature()
{
   Workbook wb = new Workbook(@"newfile.xlsx");
   //wb.IsDigitallySigned is true when the workbook is signed already.
   System.Console.WriteLine(wb.IsDigitallySigned);
   //get digitalSignature collection from workbook
   DigitalSignatureCollection dsc = wb.GetDigitalSignature();
   foreach (DigitalSignature ds in dsc)
   {
       System.Console.WriteLine(ds.Comments);
       System.Console.WriteLine(ds.SignTime);
       System.Console.WriteLine(ds.IsValid);
   }
}
internal void SignSignature()
{
   //dsc is signature collection contains one or more signature needed to sign
   DigitalSignatureCollection dsc = new DigitalSignatureCollection();
   //cert must contain private key, it can be contructed from cert file or windows certificate collection.
   //123456 is password of cert
   X509Certificate2 cert = new X509Certificate2("mykey2.pfx", "123456");
   DigitalSignature ds = new DigitalSignature(cert, "test for sign", DateTime.Now);
   dsc.Add(ds);
   Workbook wb = new Workbook();
   //wb.SetDigitalSignature sign all signatures in dsc
   wb.SetDigitalSignature(dsc);
   wb.Save(@"newfile.xlsx");
}

[Visual Basic]
   Sub ValidateSignature()
   Dim workbook As Workbook = New Workbook("newfile.xlsx")
   'Workbook.IsDigitallySigned is true when the workbook is signed already.
   System.Console.WriteLine(workbook.IsDigitallySigned)
   'get digitalSignature collection from workbook
   Dim dsc As DigitalSignatureCollection = workbook.GetDigitalSignature()
   Dim ds As DigitalSignature
   For Each ds In dsc
       System.Console.WriteLine(ds.Comments)
       System.Console.WriteLine(ds.SignTime)
       System.Console.WriteLine(ds.IsValid)
   Next
End Sub

Sub SignSignature()
   'dsc is signature collection contains one or more signature needed to sign
   Dim dsc As DigitalSignatureCollection = New DigitalSignatureCollection()
   'cert must contain private key, it can be contructed from cert file or windows certificate collection.
   Dim cert As X509Certificate2 = New X509Certificate2("mykey2.pfx", "123456")
   'create a signature with certificate, sign purpose and sign time
   Dim ds As DigitalSignature = New DigitalSignature(cert, "test for sign", DateTime.Now)
   dsc.Add(ds)
   Dim workbook As Workbook = New Workbook()
   'workbook.SetDigitalSignature sign all signatures in dsc
   workbook.SetDigitalSignature(dsc)
   workbook.Save("newfile.xlsx")
End Sub
```

### See Also

* namespace [Aspose.Cells.DigitalSignatures](../../aspose.cells.digitalsignatures)
* assembly [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->
