---
title: CreateRuleMoveContaining
second_title: Aspose.Email for .NET API Reference
description: Creates inbox rule that moves messages containing the specified strings in either the body or the subject into the specified folder
type: docs
weight: 40
url: /net/aspose.email.clients.exchange/inboxrule/createrulemovecontaining/
---
## InboxRule.CreateRuleMoveContaining method

Creates inbox rule that moves messages containing the specified strings in either the body or the subject into the specified folder

```csharp
public static InboxRule CreateRuleMoveContaining(string[] filter, string destinationFolderId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filter | String[] | A strings to search |
| destinationFolderId | String | An id of folder in which messages will be moved |

### Return Value

A created [`InboxRule`](../../inboxrule)

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *filter* is `null` or `empty` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* is `null` or `empty` |

### See Also

* class [InboxRule](../../inboxrule)
* namespace [Aspose.Email.Clients.Exchange](../../inboxrule)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
