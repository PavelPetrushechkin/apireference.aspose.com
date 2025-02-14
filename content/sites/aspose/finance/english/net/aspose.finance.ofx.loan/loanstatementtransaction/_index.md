---
title: LoanStatementTransaction
second_title: Aspose.Finance for .NET API Reference
description: This class describes a single transaction. It identifies the type of the transaction and the date it was posted.The class can also provide additional information to help the customer recognize the transaction check number name memo and images.
type: docs
weight: 3960
url: /net/aspose.finance.ofx.loan/loanstatementtransaction/
---
## LoanStatementTransaction class

This class describes a single transaction. It identifies the type of the transaction and the date it was posted.The class can also provide additional information to help the customer recognize the transaction: check number, name, memo and images.

```csharp
public class LoanStatementTransaction
```

## Constructors

| Name | Description |
| --- | --- |
| [LoanStatementTransaction](loanstatementtransaction)() | Initializes a new instance of [`LoanStatementTransaction`](../loanstatementtransaction) class. |

## Properties

| Name | Description |
| --- | --- |
| [AccountTo](../../aspose.finance.ofx.loan/loanstatementtransaction/accountto) { get; set; } | Gets or sets the to account, [`BankAccount`](../../aspose.finance.ofx/bankaccount) or [`LoanAccount`](../../aspose.finance.ofx/loanaccount). |
| [CheckNumber](../../aspose.finance.ofx.loan/loanstatementtransaction/checknumber) { get; set; } | Gets or sets the check number. |
| [CorrectFITransactionId](../../aspose.finance.ofx.loan/loanstatementtransaction/correctfitransactionid) { get; set; } | Gets or sets the corrected transaction ID. If present, the FITransactionId of a previously sent transaction that is corrected by this record. |
| [CorrectiveAction](../../aspose.finance.ofx.loan/loanstatementtransaction/correctiveaction) { get; set; } | Gets or sets the corrective action. |
| [Currency](../../aspose.finance.ofx.loan/loanstatementtransaction/currency) { get; set; } | Gets or sets the [`Currency`](./currency). |
| [ExtendedName](../../aspose.finance.ofx.loan/loanstatementtransaction/extendedname) { get; set; } | Gets or sets the extended name of payee or description of transaction. |
| [FITransactionId](../../aspose.finance.ofx.loan/loanstatementtransaction/fitransactionid) { get; set; } | Gets or sets the transaction ID issued by financial institution. |
| [ImageDatas](../../aspose.finance.ofx.loan/loanstatementtransaction/imagedatas) { get; set; } | Gets or sets the collection of [`ImageData`](../../aspose.finance.ofx/imagedata). |
| [LoanTransactionAmount](../../aspose.finance.ofx.loan/loanstatementtransaction/loantransactionamount) { get; set; } | Gets or sets the [`LoanTransactionAmount`](./loantransactionamount). |
| [LoanTransactionType](../../aspose.finance.ofx.loan/loanstatementtransaction/loantransactiontype) { get; set; } | Gets or sets the loan transaction type. |
| [Memo](../../aspose.finance.ofx.loan/loanstatementtransaction/memo) { get; set; } | Gets or sets the extra information. |
| [Name](../../aspose.finance.ofx.loan/loanstatementtransaction/name) { get; set; } | Gets or sets the name of payee or description of transaction. |
| [OriginCurrency](../../aspose.finance.ofx.loan/loanstatementtransaction/origincurrency) { get; set; } | Gets or sets the Origin [`Currency`](./currency). |
| [PostedDate](../../aspose.finance.ofx.loan/loanstatementtransaction/posteddate) { get; set; } | Gets or sets the date transaction was posted to account. |
| [ReferenceNumber](../../aspose.finance.ofx.loan/loanstatementtransaction/referencenumber) { get; set; } | Gets or sets the reference number that uniquely identifies the transaction. |
| [ServerTransactionId](../../aspose.finance.ofx.loan/loanstatementtransaction/servertransactionid) { get; set; } | Gets or sets the server assigned transaction ID. |
| [TransactionAmount](../../aspose.finance.ofx.loan/loanstatementtransaction/transactionamount) { get; set; } | Gets or sets the amount of transaction. |
| [UserDate](../../aspose.finance.ofx.loan/loanstatementtransaction/userdate) { get; set; } | Gets or sets the date user initiated transaction, if known. |

### See Also

* namespace [Aspose.Finance.Ofx.Loan](../../aspose.finance.ofx.loan)
* assembly [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
