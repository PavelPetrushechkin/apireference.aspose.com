---
title: SetReadFlagAsync
second_title: Aspose.Email for .NET API Reference
description: Marks the specified message as read.
type: docs
weight: 630
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/setreadflagasync/
---
## IAsyncEwsClient.SetReadFlagAsync method

Marks the specified message as read.

```csharp
public Task SetReadFlagAsync(string messageUri, bool isRead = true, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | A message uri. |
| isRead | Boolean | A value indicating whether the message was read |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *messageUri* is `null` or `empty`. |

### See Also

* interface [IAsyncEwsClient](../../iasyncewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
