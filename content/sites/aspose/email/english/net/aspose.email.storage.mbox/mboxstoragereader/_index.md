---
title: MboxStorageReader
second_title: Aspose.Email for .NET API Reference
description: A base class for any mboxbased mail storage reader.
type: docs
weight: 20040
url: /net/aspose.email.storage.mbox/mboxstoragereader/
---
## MboxStorageReader class

A base class for any mbox-based mail storage reader.

```csharp
public abstract class MboxStorageReader : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream) { get; } | Gets the base stream. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize) { get; } | Gets the number of bytes that is read by ReadNextMessage method. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader#createreader)(Stream, MboxLoadOptions) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader#createreader_3)(string, MboxLoadOptions) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader#createreader_1)(Stream, MboxLoadOptions, CancellationToken) | Creates the instance of reader. |
| static [CreateReader](../../aspose.email.storage.mbox/mboxstoragereader/createreader#createreader_4)(string, MboxLoadOptions, CancellationToken) | Creates the instance of reader. |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages#enumeratemessages)() | Exposes the enumerator, which supports an iteration of messages in storage. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages#enumeratemessages_1)(EmlLoadOptions) | Exposes the enumerator, which supports an iteration of messages in storage. |
| abstract [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxstoragereader/gettotalitemscount)() | Returns the number of messages in a storage. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage#readnextmessage)() | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage#readnextmessage_1)(EmlLoadOptions) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage#readnextmessage_2)(out string) | Reads the next message from underlying storage stream. |
| abstract [ReadNextMessage](../../aspose.email.storage.mbox/mboxstoragereader/readnextmessage#readnextmessage_3)(out string, EmlLoadOptions) | Reads the next message from underlying storage stream. |

### See Also

* namespace [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
