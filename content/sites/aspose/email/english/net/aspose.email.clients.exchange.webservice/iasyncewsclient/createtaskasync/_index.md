---
title: CreateTaskAsync
second_title: Aspose.Email for .NET API Reference
description: Creates the given task in the specified folder.
type: docs
weight: 140
url: /net/aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync/
---
## IAsyncEwsClient.CreateTaskAsync method

Creates the given task in the specified folder.

```csharp
public Task<string> CreateTaskAsync(ExchangeTask task, string folder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| task | ExchangeTask | A task to create. |
| folder | String | A folder where task should be created. The folder [`TasksUri`](../../../aspose.email.clients.exchange/exchangemailboxinfo/tasksuri) is used by default. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* is `null`. |

### See Also

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
