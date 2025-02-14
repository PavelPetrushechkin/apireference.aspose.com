---
title: ChangeMessages
second_title: Aspose.Email for .NET API Reference
description: Changes the messages in folder.
type: docs
weight: 200
url: /net/aspose.email.storage.pst/folderinfo/changemessages/
---
## ChangeMessages(IEnumerable&lt;string&gt;, MapiPropertyCollection) {#changemessages_1}

Changes the messages in folder.

```csharp
public void ChangeMessages(IEnumerable<string> entryIdCollection, 
    MapiPropertyCollection updatedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| entryIdCollection | IEnumerable`1 | The entry identifier collection. |
| updatedProperties | MapiPropertyCollection | The updated properties. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The ANSI file version editing is not implemented. |
| InvalidOperationException | The PST is open for reading only. or The entryId is incorrect. |
| ArgumentNullException | entryIdCollection;The collection of entry ids cannot be null. or updatedProperties;The collection of properties cannot be null. |

### See Also

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [FolderInfo](../../folderinfo)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo)
* assembly [Aspose.Email](../../../)

---

## ChangeMessages(MapiPropertyCollection) {#changemessages}

Changes all messages in folder.

```csharp
public void ChangeMessages(MapiPropertyCollection updatedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| updatedProperties | MapiPropertyCollection | The updated properties. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | The ANSI file version editing is not implemented. |
| InvalidOperationException | The PST is open for reading only. or The entryId is incorrect. |
| ArgumentNullException | entryIdCollection;The collection of entry ids cannot be null. or updatedProperties;The collection of properties cannot be null. |

### See Also

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [FolderInfo](../../folderinfo)
* namespace [Aspose.Email.Storage.Pst](../../folderinfo)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
