---
title: MarkAsJunk
second_title: Aspose.Email for .NET API Reference
description: The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.
type: docs
weight: 1270
url: /net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | Boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | String[] | Array of message uri |

### Return Value

Returns the array of message ID which are moved to the junk mail folder.

### See Also

* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | Boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | String[] | Array of message uri |

### Return Value

Returns the array of message ID which are moved to the junk mail folder.

### See Also

* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | Boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| messageUriEn | IEnumerable`1 | Enumeration of message uri |

### Return Value

Returns the item ID of the message marked as junk mail.

### See Also

* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | Boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | IEnumerable`1 | Enumeration of message uri |

### Return Value

Returns the array of message ID which are moved to the junk mail folder.

### See Also

* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

The MarkAsJunk method moves mail messages to the junk mail folder and blocks message sender.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isJunk | Boolean | Indicates, whether messages is marked as junk mail. If value of true adds message sender to the block-list. If value of false removes message sender from the block-list. |
| moveItem | Boolean | Indicates, whether messages is moved to the junk mail folder. |
| messageUriEn | IEnumerable`1 | Enumeration of message uri |
| movedMessageIds | String[]& | Returns the array of message ID which are moved to the junk mail folder. |
| failedMessageIds | String[]& | Returns the array of message ID which haven't been moved to the junk mail folder. |
| errorMessages | String[]& | Error messages for failed operations |

### See Also

* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
