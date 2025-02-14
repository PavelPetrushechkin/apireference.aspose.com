---
title: AccountSyncResponse
second_title: Aspose.Finance for .NET API Reference
description: Service activation synchronization response class.
type: docs
weight: 5510
url: /net/aspose.finance.ofx.signup/accountsyncresponse/
---
## AccountSyncResponse class

Service activation synchronization response class.

```csharp
public class AccountSyncResponse : AbstractSyncResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [AccountSyncResponse](accountsyncresponse)() | Initializes a new instance of [`AccountSyncResponse`](../accountsyncresponse) class. |

## Properties

| Name | Description |
| --- | --- |
| [AccountTransactionResponses](../../aspose.finance.ofx.signup/accountsyncresponse/accounttransactionresponses) { get; set; } | Gets or sets the collection of [`AccountTransactionResponse`](../accounttransactionresponse). |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Yes if the token in the synchronization request is older than the earliest entry in the server’s history table.In this case, some responses have been lost. No if the token in the synchronization request is newer than or matches a token in the server’s history table. |
| [OfxExtension](../../aspose.finance.ofx.signup/accountsyncresponse/ofxextension) { get; set; } | Gets or sets the [`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype). |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Gets or sets the new synchronization token. |

### See Also

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* namespace [Aspose.Finance.Ofx.Signup](../../aspose.finance.ofx.signup)
* assembly [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
