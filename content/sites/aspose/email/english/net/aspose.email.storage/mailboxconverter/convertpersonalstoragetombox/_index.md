---
title: ConvertPersonalStorageToMbox
second_title: Aspose.Email for .NET API Reference
description: Converts the PersonalStorageaspose.email.storage.pst/personalstorage to mbox format using given path.
type: docs
weight: 10
url: /net/aspose.email.storage/mailboxconverter/convertpersonalstoragetombox/
---
## ConvertPersonalStorageToMbox(PersonalStorage, string, MessageAcceptanceCallback) {#convertpersonalstoragetombox_1}

Converts the [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) to mbox format using given path.

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    string storagePath, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| personalStorage | PersonalStorage | The personal storage. |
| storagePath | String | The path to save *personalStorage* structure to. |
| acceptanceCallback | MessageAcceptanceCallback | The acceptance callback, can be null. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *personalStorage* is null. |
| ArgumentNullException | If *storagePath* is null. |

### Remarks

Resulting folder will contain an exact copy of the *personalStorage* e.g. directory tree will be recreated on disk.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* namespace [Aspose.Email.Storage](../../mailboxconverter)
* assembly [Aspose.Email](../../../)

---

## ConvertPersonalStorageToMbox(PersonalStorage, MboxStorageWriter, MessageAcceptanceCallback) {#convertpersonalstoragetombox}

Converts the [`PersonalStorage`](../../../aspose.email.storage.pst/personalstorage) to mbox format using given [`MboxStorageWriter`](../../../aspose.email.storage.mbox/mboxstoragewriter).

```csharp
public static void ConvertPersonalStorageToMbox(PersonalStorage personalStorage, 
    MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| personalStorage | PersonalStorage | The personal storage. |
| mboxStorageWriter | MboxStorageWriter | The mbox storage writer. |
| acceptanceCallback | MessageAcceptanceCallback | The acceptance callback, can be null. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *personalStorage* is null. |
| ArgumentNullException | If *mboxStorageWriter* is null. |

### Remarks

Resulting mbox storage will contain only one plain inbox folder with all messages, if you have to preserve the original structure of the storage, use XXX_method instead.

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage)
* class [MboxStorageWriter](../../../aspose.email.storage.mbox/mboxstoragewriter)
* delegate [MessageAcceptanceCallback](../../../aspose.email/messageacceptancecallback)
* class [MailboxConverter](../../mailboxconverter)
* namespace [Aspose.Email.Storage](../../mailboxconverter)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
