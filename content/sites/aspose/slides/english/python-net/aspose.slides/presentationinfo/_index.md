---
title: PresentationInfo
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 3550
url: /python-net/aspose.slides/presentationinfo/
---

## PresentationInfo class

Information about presentation file

The PresentationInfo type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_encrypted|Gets True if binded presentation is encrypted, otherwise False.<br/>            Read-only bool.|
|is_password_protected|Gets a value that indicates whether a binded presentation is protected by a password to open.|
|is_write_protected|Gets a value that indicates whether a binded presentation is write protected.|
|load_format|Gets format of the binded presentation.<br/>            Read-only [LoadFormat](/slides/python-net/aspose.slides/loadformat/).|
## Methods
| Name | Description |
| :- | :- |
|write_binded_presentation(stream)|Writes binded presentation to stream.|
|write_binded_presentation(file)|Writes binded presentation to file.|
|check_password(password)|Checks whether a password is correct for a presentation protected with open password.|
|check_write_protection(password)|Checks whether a password to modify is correct for a write protected presentation.|
|read_document_properties()|Gets document properties of binded presentation.|
|update_document_properties(document_properties)|Updates properties of binded presentation.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

