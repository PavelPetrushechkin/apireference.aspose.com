---
title: BodyRtf
second_title: Aspose.Email for .NET API Reference
description: Gets or sets the RTF formatted message text.
type: docs
weight: 50
url: /net/aspose.email.mapi/mapimessageitembase/bodyrtf/
---
## MapiMessageItemBase.BodyRtf property

Gets or sets the RTF formatted message text.

```csharp
public string BodyRtf { get; set; }
```

### Property Value

The string that represents message body rtf.

### Remarks

When setting a value, the values of PR_RTF_COMPRESSED, PR_RTF_DECOMPRESSES, PR_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

### See Also

* class [MapiMessageItemBase](../../mapimessageitembase)
* namespace [Aspose.Email.Mapi](../../mapimessageitembase)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
