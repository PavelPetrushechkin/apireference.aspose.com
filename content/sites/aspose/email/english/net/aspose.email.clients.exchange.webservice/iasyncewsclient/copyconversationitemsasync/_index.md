---
title: CopyConversationItemsAsync
second_title: Aspose.Email for .NET API Reference
description: Copies the conversation items which are located in the specified folder into the specified target folder
type: docs
weight: 70
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync/
---
## IAsyncEwsClient.CopyConversationItemsAsync method

Copies the conversation items, which are located in the specified folder, into the specified target folder

```csharp
public Task CopyConversationItemsAsync(string conversationId, string destinationFolderId, 
    string contextFolderId = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to copy |
| destinationFolderId | String | Id of folder into which copy items |
| contextFolderId | String | Id of folder in which conversation items are located. Note: If it's set to null(or empty), all conversation items will be copied |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* is `null` or `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* is `null` or `empty` |

### See Also

* interface [IAsyncEwsClient](../../iasyncewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
