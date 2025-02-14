---
title: DeleteConversationItemsAsync
second_title: Aspose.Email for .NET API Reference
description: Deletes the conversation items which are located in the specified folder
type: docs
weight: 150
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/deleteconversationitemsasync/
---
## IAsyncEwsClient.DeleteConversationItemsAsync method

Deletes the conversation items, which are located in the specified folder

```csharp
public Task DeleteConversationItemsAsync(string conversationId, string contextFolderId = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| conversationId | String | Id of conversation to delete |
| contextFolderId | String | Id of folder in which delete conversation items. Note: If it's set to null(or empty), all conversation items will be deleted |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* is `null` or `empty` |

### See Also

* interface [IAsyncEwsClient](../../iasyncewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
