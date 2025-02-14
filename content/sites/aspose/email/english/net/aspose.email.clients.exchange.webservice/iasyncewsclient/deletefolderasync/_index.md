---
title: DeleteFolderAsync
second_title: Aspose.Email for .NET API Reference
description: Deletes the folder
type: docs
weight: 160
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/deletefolderasync/
---
## IAsyncEwsClient.DeleteFolderAsync method

Deletes the folder

```csharp
public Task DeleteFolderAsync(string folderUri, bool deletePermanently = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The folder URI |
| deletePermanently | Boolean | Indicates whether the folder should be deleted permanently or should be moved into DeletedItems folder |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderUri* is `null` or empty |

### See Also

* interface [IAsyncEwsClient](../../iasyncewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
