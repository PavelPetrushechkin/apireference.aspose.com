---
title: LoadFromTnef
second_title: Aspose.Email for .NET API Reference
description: Loads message from Transport Neutral Encapsulation Format TNEF data structure
type: docs
weight: 50
url: /net/aspose.email.mapi/mapimessage/loadfromtnef/
---
## LoadFromTnef(Stream) {#loadfromtnef}

Loads message from Transport Neutral Encapsulation Format (TNEF) data structure

```csharp
public static MapiMessage LoadFromTnef(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream representing message data in TNEF format |

### Return Value

A read [`MapiMessage`](../../mapimessage)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [MapiMessage](../../mapimessage)
* namespace [Aspose.Email.Mapi](../../mapimessage)
* assembly [Aspose.Email](../../../)

---

## LoadFromTnef(string) {#loadfromtnef_1}

Loads message from Transport Neutral Encapsulation Format (TNEF) data structure

```csharp
public static MapiMessage LoadFromTnef(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of file containing message data in TNEF format |

### Return Value

A read [`MapiMessage`](../../mapimessage)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty` |

### See Also

* class [MapiMessage](../../mapimessage)
* namespace [Aspose.Email.Mapi](../../mapimessage)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
