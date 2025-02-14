---
title: SaveMessage
second_title: Aspose.Email for .NET API Reference
description: Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format EML. if you want to parse the mail message files use MailMessageaspose.email/mailmessage.
type: docs
weight: 360
url: /net/aspose.email.clients.exchange.dav/exchangeclient/savemessage/
---
## SaveMessage(string, string) {#savemessage_1}

Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML). if you want to parse the mail message files, use [`MailMessage`](../../../aspose.email/mailmessage).

```csharp
public void SaveMessage(string messageUri, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | The Uri of the mail message |
| path | String | The target path to save the message |

### See Also

* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(string, Stream) {#savemessage}

Saves the message.

```csharp
public void SaveMessage(string messageUri, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | String | The message URI. |
| stream | Stream | The stream. |

### See Also

* class [ExchangeClient](../../exchangeclient)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
