---
title: ExchangeClient
second_title: Aspose.Email for Java API Reference
description: The ExchangeClient class allows applications to manage E-Mail box in Microsoft Exchange Server by using WebDav Exchange Store Protocol.
type: docs
weight: 195
url: /java/com.aspose.email/exchangeclient/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.ExchangeClientBase](../../com.aspose.email/exchangeclientbase)
```
public final class ExchangeClient extends ExchangeClientBase
```

\`\`\`

The ExchangeClient class allows applications to manage E-Mail box in Microsoft Exchange Server by using WebDav Exchange Store Protocol.

\`\`\`
## Constructors

| Constructor | Description |
| --- | --- |
| [ExchangeClient(String mailboxUri, String username, String password)](#ExchangeClient-java.lang.String-java.lang.String-java.lang.String-) | Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient) |
| [ExchangeClient(String mailboxUri, String username, String password, String domain)](#ExchangeClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient) |
| [ExchangeClient(String mailboxUri, System.Net.ICredentials credentials)](#ExchangeClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-) | Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient) |
## Methods

| Method | Description |
| --- | --- |
| [getClientCertificate()](#getClientCertificate--) | Gets or sets the client certificate. |
| [setClientCertificate(System.Security.Cryptography.X509Certificates.X509Certificate value)](#setClientCertificate-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate-) | Gets or sets the client certificate. |
| [getKeepAlive()](#getKeepAlive--) | Indicates whether to keep alive. |
| [setKeepAlive(boolean value)](#setKeepAlive-boolean-) | Indicates whether to keep alive. |
| [getPreAuthenticate()](#getPreAuthenticate--) | Indicates whether to do pre-authentication. |
| [setPreAuthenticate(boolean value)](#setPreAuthenticate-boolean-) | Indicates whether to do pre-authentication. |
| [getEncoding()](#getEncoding--) | Gets or sets the encoding. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Gets or sets the encoding. |
| [getMailboxInfo()](#getMailboxInfo--) | Gets the mailbox information. |
| [getCookieContainer()](#getCookieContainer--) | Gets or sets the cookie container. |
| [setCookieContainer(System.Net.CookieContainer value)](#setCookieContainer-com.aspose.ms.System.Net.CookieContainer-) | Gets or sets the cookie container. |
| [getSendChunked()](#getSendChunked--) | Gets or sets a value indicating whether [send chunked]. |
| [setSendChunked(boolean value)](#setSendChunked-boolean-) | Gets or sets a value indicating whether [send chunked]. |
| [moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri)](#moveMessage-com.aspose.email.ExchangeMessageInfo-java.lang.String-) | Moves the message. |
| [moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri, boolean overwrite)](#moveMessage-com.aspose.email.ExchangeMessageInfo-java.lang.String-boolean-) | Moves the message. |
| [moveMessage(String destinationFolderUri, String messageUri)](#moveMessage-java.lang.String-java.lang.String-) | Moves the message. |
| [moveMessage(String destinationFolderUri, boolean overwrite, String messageUri)](#moveMessage-java.lang.String-boolean-java.lang.String-) | Moves the message. |
| [moveItems(String destinationFolderUri, String[] itemsUriArray)](#moveItems-java.lang.String-java.lang.String...-) | Moves items. |
| [moveItems(String destinationFolderUri, boolean overwrite, String[] itemsUriArray)](#moveItems-java.lang.String-boolean-java.lang.String...-) | Moves items. |
| [getMailboxSize()](#getMailboxSize--) | Get the size of the maibox |
| [getMailboxSize(String mailbox)](#getMailboxSize-java.lang.String-) | Get the size of the maibox |
| [getVersionInfo()](#getVersionInfo--) | Returns exchange server version info |
| [getMailboxInfo(String mailbox)](#getMailboxInfo-java.lang.String-) | Gets the mailbox information |
| [listMessages(String folder, String messageClass, boolean recursive)](#listMessages-java.lang.String-java.lang.String-boolean-) | Lists the messages. |
| [listMessages(String folder, boolean recursive)](#listMessages-java.lang.String-boolean-) | List the messages in the specified folder |
| [listMessages(String folder, String query)](#listMessages-java.lang.String-java.lang.String-) | Lists the messages. |
| [listMessages(String folder, MailQuery query, boolean recursive)](#listMessages-java.lang.String-com.aspose.email.MailQuery-boolean-) | Lists the messages. |
| [listMessagesById(String folder, String messageId)](#listMessagesById-java.lang.String-java.lang.String-) | Lists the messages by id. |
| [listMessagesByOption(String folder, int options)](#listMessagesByOption-java.lang.String-int-) | Lists the mail message in the specified folder. |
| [saveMessage(String messageUri, String path)](#saveMessage-java.lang.String-java.lang.String-) | Saves mail message specified by the uri to local file system. |
| [saveMessage(String messageUri, OutputStream stream)](#saveMessage-java.lang.String-java.io.OutputStream-) | Saves the message. |
| [saveMessageInternal(String messageUri, System.IO.Stream stream)](#saveMessageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [send(MailMessage message)](#send-com.aspose.email.MailMessage-) | Sends the mail message. |
| [setReadFlag(String messageUri)](#setReadFlag-java.lang.String-) | Marks the specifeid message as read. |
| [setReadFlag(String messageUri, boolean suppressReceipt)](#setReadFlag-java.lang.String-boolean-) | Marks the specifeid message as read. |
| [listPublicFolders()](#listPublicFolders--) | Gets collection of public folders from root public folder |
| [listSubFolders(String parentFolderUri)](#listSubFolders-java.lang.String-) | Gets collection of child folders from parent |
| [fetchMessage(String messageUri)](#fetchMessage-java.lang.String-) | Fetches the mail message with specified uri. |
| [fetchMapiMessage(String messageUri)](#fetchMapiMessage-java.lang.String-) | Fetches the mapi message with specified uri. |
| [deleteMessage(String messageUri)](#deleteMessage-java.lang.String-) | Deletes the mail message. |
| [deleteMessage(String messageUri, boolean suppressReceipt)](#deleteMessage-java.lang.String-boolean-) | Deletes the mail message. |
| [appendMessage(String folder, MailMessage message)](#appendMessage-java.lang.String-com.aspose.email.MailMessage-) | Uploads the mail message to the specified folder |
| [appendMessage(String folder, MailMessage message, boolean markAsSent)](#appendMessage-java.lang.String-com.aspose.email.MailMessage-boolean-) | Uploads the mail message to the specified folder |
| [listMessagesByOption(String folder, int maxNumberOfMessages, int options)](#listMessagesByOption-java.lang.String-int-int-) | List the messages in the specified folder |
| [fetchAttachment(String attachmentUri)](#fetchAttachment-java.lang.String-) | Fetches the attachment |
| [backup(ExchangeFolderInfoCollection folders, String fileName, int options)](#backup-com.aspose.email.ExchangeFolderInfoCollection-java.lang.String-int-) | Backups the content of the specified folders |
| [backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options)](#backup-com.aspose.email.ExchangeFolderInfoCollection-java.io.OutputStream-int-) | Backups the content of the specified folders |
| [backupInternal(ExchangeFolderInfoCollection folders, System.IO.Stream stream, int options)](#backupInternal-com.aspose.email.ExchangeFolderInfoCollection-com.aspose.ms.System.IO.Stream-int-) |  |
| [getFolderInfo(String folderUri)](#getFolderInfo-java.lang.String-) | Gets the folder information. |
| [folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder)](#folderExists-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderInfo---) | Checks whether the specified folder exists. |
| [createFolder(String parentFolderUri, String name)](#createFolder-java.lang.String-java.lang.String-) | Creates the new folder with the specified name in the specified parent folder. |
| [deleteFolder(String folderUri)](#deleteFolder-java.lang.String-) | Deletes the folder |
| [restore(String fileName, int options)](#restore-java.lang.String-int-) | Restores exchange folders from the specified personal storage file. |
| [restore(InputStream stream, int options)](#restore-java.io.InputStream-int-) | Restores exchange folders from the given personal storage. |
| [restoreInternal(System.IO.Stream stream, int options)](#restoreInternal-com.aspose.ms.System.IO.Stream-int-) |  |
| [restore(PersonalStorage pst, int options)](#restore-com.aspose.email.PersonalStorage-int-) | Restores exchange folders from the given personal storage. |
| [restore(String fileName, ExchangeFolderInfoCollection folders, int options)](#restore-java.lang.String-com.aspose.email.ExchangeFolderInfoCollection-int-) | Restores the specified exchange folders from the specified personal storage file. |
| [restore(InputStream stream, ExchangeFolderInfoCollection folders, int options)](#restore-java.io.InputStream-com.aspose.email.ExchangeFolderInfoCollection-int-) | Restores the specified exchange folders from the given personal storage. |
| [restoreInternal(System.IO.Stream stream, ExchangeFolderInfoCollection folders, int options)](#restoreInternal-com.aspose.ms.System.IO.Stream-com.aspose.email.ExchangeFolderInfoCollection-int-) |  |
| [restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, int options)](#restore-com.aspose.email.PersonalStorage-com.aspose.email.ExchangeFolderInfoCollection-int-) | Restores the specified exchange folders from the given personal storage. |
| [createContact(Contact contact)](#createContact-com.aspose.email.Contact-) | Creates a contact item in the Exchange store. |
| [deleteContact(Contact contact)](#deleteContact-com.aspose.email.Contact-) | Deletes the contact. |
| [deleteContact(MapiContact contact)](#deleteContact-com.aspose.email.MapiContact-) | Deletes the contact. |
| [deleteContact(String id)](#deleteContact-java.lang.String-) | Deletes the contact. |
| [getContacts(String folderUri)](#getContacts-java.lang.String-) | Lists contacts located in the specified folder on server |
| [listContacts(String folderUri)](#listContacts-java.lang.String-) | Lists contacts located in the specified folder on server |
| [resolveContacts(String unresolvedEntry)](#resolveContacts-java.lang.String-) | Resolves ambiguous mailbox display names. |
| [listMailboxes()](#listMailboxes--) | Lists mailboxes in the global address list. |
| [getMailboxes()](#getMailboxes--) | Lists mailboxes in the global address list. |
| [listSubFolders(ExchangeFolderInfo parentFolder)](#listSubFolders-com.aspose.email.ExchangeFolderInfo-) | Gets collection of child public folders from parent |
| [listMessages(String folder)](#listMessages-java.lang.String-) | Lists the messages. |
| [listMessages(String folder, int maxNumberOfMessages)](#listMessages-java.lang.String-int-) | Lists the messages. |
| [listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages)](#listMessagesByMaxNumberOfMessages-java.lang.String-int-) | Lists the messages. |
| [folderExists(String parentFolderUri, String folderName)](#folderExists-java.lang.String-java.lang.String-) | Checks whether the specified folder exists. |
### ExchangeClient(String mailboxUri, String username, String password) {#ExchangeClient-java.lang.String-java.lang.String-java.lang.String-}
```
public ExchangeClient(String mailboxUri, String username, String password)
```


Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The url of the mailbox |
| username | java.lang.String | The username of the mailbox |
| password | java.lang.String | The password of the mailbox |

### ExchangeClient(String mailboxUri, String username, String password, String domain) {#ExchangeClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public ExchangeClient(String mailboxUri, String username, String password, String domain)
```


Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The url of the mailbox |
| username | java.lang.String | The username of the mailbox |
| password | java.lang.String | The password of the mailbox |
| domain | java.lang.String | The domain of the user |

### ExchangeClient(String mailboxUri, System.Net.ICredentials credentials) {#ExchangeClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-}
```
public ExchangeClient(String mailboxUri, System.Net.ICredentials credentials)
```


Initialize a new instance of the class [ExchangeClient](../../com.aspose.email/exchangeclient)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The url of the mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | The credentials used to log in |

### getClientCertificate() {#getClientCertificate--}
```
public final System.Security.Cryptography.X509Certificates.X509Certificate getClientCertificate()
```


Gets or sets the client certificate.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate
### setClientCertificate(System.Security.Cryptography.X509Certificates.X509Certificate value) {#setClientCertificate-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate-}
```
public final void setClientCertificate(System.Security.Cryptography.X509Certificates.X509Certificate value)
```


Gets or sets the client certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate |  |

### getKeepAlive() {#getKeepAlive--}
```
public final boolean getKeepAlive()
```


Indicates whether to keep alive.

**Returns:**
boolean
### setKeepAlive(boolean value) {#setKeepAlive-boolean-}
```
public final void setKeepAlive(boolean value)
```


Indicates whether to keep alive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreAuthenticate() {#getPreAuthenticate--}
```
public final boolean getPreAuthenticate()
```


Indicates whether to do pre-authentication.

**Returns:**
boolean
### setPreAuthenticate(boolean value) {#setPreAuthenticate-boolean-}
```
public final void setPreAuthenticate(boolean value)
```


Indicates whether to do pre-authentication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gets or sets the encoding.

**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Gets or sets the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### getMailboxInfo() {#getMailboxInfo--}
```
public final ExchangeMailboxInfo getMailboxInfo()
```


Gets the mailbox information.

**Returns:**
[ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo)
### getCookieContainer() {#getCookieContainer--}
```
public final System.Net.CookieContainer getCookieContainer()
```


Gets or sets the cookie container.

Value: The cookie container.

**Returns:**
com.aspose.ms.System.Net.CookieContainer
### setCookieContainer(System.Net.CookieContainer value) {#setCookieContainer-com.aspose.ms.System.Net.CookieContainer-}
```
public final void setCookieContainer(System.Net.CookieContainer value)
```


Gets or sets the cookie container.

Value: The cookie container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Net.CookieContainer |  |

### getSendChunked() {#getSendChunked--}
```
public final boolean getSendChunked()
```


Gets or sets a value indicating whether [send chunked].

Value: \`\`\` true \`\`\` if [send chunked]; otherwise, \`\`\` false \`\`\`.

**Returns:**
boolean
### setSendChunked(boolean value) {#setSendChunked-boolean-}
```
public final void setSendChunked(boolean value)
```


Gets or sets a value indicating whether [send chunked].

Value: \`\`\` true \`\`\` if [send chunked]; otherwise, \`\`\` false \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri) {#moveMessage-com.aspose.email.ExchangeMessageInfo-java.lang.String-}
```
public final void moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri)
```


Moves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msgInfo | [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) | Represents the E-Mail message info fetched from the Exchange Store. |
| destinationFolderUri | java.lang.String | An URI of a destination folder. |

### moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri, boolean overwrite) {#moveMessage-com.aspose.email.ExchangeMessageInfo-java.lang.String-boolean-}
```
public final void moveMessage(ExchangeMessageInfo msgInfo, String destinationFolderUri, boolean overwrite)
```


Moves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| msgInfo | [ExchangeMessageInfo](../../com.aspose.email/exchangemessageinfo) | Represents the E-Mail message info fetched from the Exchange Store. |
| destinationFolderUri | java.lang.String | An URI of a destination folder. |
| overwrite | boolean | Specifies whether the server should overwrite a existing message while processing a MOVE operation. |

### moveMessage(String destinationFolderUri, String messageUri) {#moveMessage-java.lang.String-java.lang.String-}
```
public final void moveMessage(String destinationFolderUri, String messageUri)
```


Moves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationFolderUri | java.lang.String | An URI of a destination folder. |
| messageUri | java.lang.String | Represents the uri of E-Mail message. |

### moveMessage(String destinationFolderUri, boolean overwrite, String messageUri) {#moveMessage-java.lang.String-boolean-java.lang.String-}
```
public final void moveMessage(String destinationFolderUri, boolean overwrite, String messageUri)
```


Moves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationFolderUri | java.lang.String | An URI of a destination folder. |
| overwrite | boolean | Specifies whether the server should overwrite a existing message while processing a MOVE operation. |
| messageUri | java.lang.String | Represents the uri of E-Mail message. |

### moveItems(String destinationFolderUri, String[] itemsUriArray) {#moveItems-java.lang.String-java.lang.String...-}
```
public final void moveItems(String destinationFolderUri, String[] itemsUriArray)
```


Moves items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationFolderUri | java.lang.String | The new destination for items. |
| itemsUriArray | java.lang.String[] | Items uri arrray |

### moveItems(String destinationFolderUri, boolean overwrite, String[] itemsUriArray) {#moveItems-java.lang.String-boolean-java.lang.String...-}
```
public final void moveItems(String destinationFolderUri, boolean overwrite, String[] itemsUriArray)
```


Moves items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationFolderUri | java.lang.String | The new destination for items. |
| overwrite | boolean | Specifies whether the server should overwrite a existing message while processing a MOVE operation. |
| itemsUriArray | java.lang.String[] | Items uri arrray |

### getMailboxSize() {#getMailboxSize--}
```
public final long getMailboxSize()
```


Get the size of the maibox

**Returns:**
long - The size of the mailbox
### getMailboxSize(String mailbox) {#getMailboxSize-java.lang.String-}
```
public final long getMailboxSize(String mailbox)
```


Get the size of the maibox

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox. Note: if it is set to \`\`\` null \`\`\` or \`\`\` empty \`\`\` the default mailbox will be used |

**Returns:**
long - The size of the mailbox
### getVersionInfo() {#getVersionInfo--}
```
public final String getVersionInfo()
```


Returns exchange server version info

**Returns:**
java.lang.String - Returns exchange server version info
### getMailboxInfo(String mailbox) {#getMailboxInfo-java.lang.String-}
```
public final ExchangeMailboxInfo getMailboxInfo(String mailbox)
```


Gets the mailbox information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | java.lang.String | A mailbox to read from. Note: if mailbox is set to \`\`\` null \`\`\` or \`\`\` empty \`\`\` the default mailbox will be used |

**Returns:**
[ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) - [ExchangeMailboxInfo](../../com.aspose.email/exchangemailboxinfo) that represents mailbox information
### listMessages(String folder, String messageClass, boolean recursive) {#listMessages-java.lang.String-java.lang.String-boolean-}
```
public final ExchangeMessageInfoCollection listMessages(String folder, String messageClass, boolean recursive)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| messageClass | java.lang.String | The message class. |
| recursive | boolean | if set to \`\`\` true \`\`\` [recursive]. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - 
### listMessages(String folder, boolean recursive) {#listMessages-java.lang.String-boolean-}
```
public final ExchangeMessageInfoCollection listMessages(String folder, boolean recursive)
```


List the messages in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder Uri |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A collection of message info
### listMessages(String folder, String query) {#listMessages-java.lang.String-java.lang.String-}
```
public final ExchangeMessageInfoCollection listMessages(String folder, String query)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| query | java.lang.String | The query. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - 
### listMessages(String folder, MailQuery query, boolean recursive) {#listMessages-java.lang.String-com.aspose.email.MailQuery-boolean-}
```
public final ExchangeMessageInfoCollection listMessages(String folder, MailQuery query, boolean recursive)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The Uri of folder that contains messages. |
| query | [MailQuery](../../com.aspose.email/mailquery) | The [MailQuery](../../com.aspose.email/mailquery) that represents search criteria. |
| recursive | boolean | Indicates whether recursive listing or not. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - The message info collection.
### listMessagesById(String folder, String messageId) {#listMessagesById-java.lang.String-java.lang.String-}
```
public final ExchangeMessageInfoCollection listMessagesById(String folder, String messageId)
```


Lists the messages by id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| messageId | java.lang.String | The message id. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - 
### listMessagesByOption(String folder, int options) {#listMessagesByOption-java.lang.String-int-}
```
public final ExchangeMessageInfoCollection listMessagesByOption(String folder, int options)
```


Lists the mail message in the specified folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder url |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) collection.
### saveMessage(String messageUri, String path) {#saveMessage-java.lang.String-java.lang.String-}
```
public final void saveMessage(String messageUri, String path)
```


Saves mail message specified by the uri to local file system. The mail message file is RFC 822 compliant format (EML).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The Uri of the mail message |
| path | java.lang.String | The target path to save the message

--------------------

if you want to parse the mail message files, use [MailMessage](../../com.aspose.email/mailmessage). |

### saveMessage(String messageUri, OutputStream stream) {#saveMessage-java.lang.String-java.io.OutputStream-}
```
public final void saveMessage(String messageUri, OutputStream stream)
```


Saves the message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message URI. |
| stream | java.io.OutputStream | The stream. |

### saveMessageInternal(String messageUri, System.IO.Stream stream) {#saveMessageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public void saveMessageInternal(String messageUri, System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String |  |
| stream | com.aspose.ms.System.IO.Stream |  |

### send(MailMessage message) {#send-com.aspose.email.MailMessage-}
```
public final void send(MailMessage message)
```


Sends the mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The mail message to be sent. |

### setReadFlag(String messageUri) {#setReadFlag-java.lang.String-}
```
public final void setReadFlag(String messageUri)
```


Marks the specifeid message as read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | A message uri. |

### setReadFlag(String messageUri, boolean suppressReceipt) {#setReadFlag-java.lang.String-boolean-}
```
public final void setReadFlag(String messageUri, boolean suppressReceipt)
```


Marks the specifeid message as read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | A message uri. |
| suppressReceipt | boolean | A value indicating whether the sending a read receipt should be suppressed. |

### listPublicFolders() {#listPublicFolders--}
```
public final ExchangeFolderInfoCollection listPublicFolders()
```


Gets collection of public folders from root public folder

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the root public folder
### listSubFolders(String parentFolderUri) {#listSubFolders-java.lang.String-}
```
public final ExchangeFolderInfoCollection listSubFolders(String parentFolderUri)
```


Gets collection of child folders from parent

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | The uri of the parent folder |

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the parent folder
### fetchMessage(String messageUri) {#fetchMessage-java.lang.String-}
```
public final MailMessage fetchMessage(String messageUri)
```


Fetches the mail message with specified uri.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message uri. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A MailMessage object contains the message.
### fetchMapiMessage(String messageUri) {#fetchMapiMessage-java.lang.String-}
```
public final MapiMessage fetchMapiMessage(String messageUri)
```


Fetches the mapi message with specified uri.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message uri. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A [MapiMessage](../../com.aspose.email/mapimessage) object contains the message.
### deleteMessage(String messageUri) {#deleteMessage-java.lang.String-}
```
public final void deleteMessage(String messageUri)
```


Deletes the mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message uri. |

### deleteMessage(String messageUri, boolean suppressReceipt) {#deleteMessage-java.lang.String-boolean-}
```
public final void deleteMessage(String messageUri, boolean suppressReceipt)
```


Deletes the mail message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageUri | java.lang.String | The message uri. |
| suppressReceipt | boolean | A value indicating whether the sending a non-read report should be suppressed. |

### appendMessage(String folder, MailMessage message) {#appendMessage-java.lang.String-com.aspose.email.MailMessage-}
```
public final String appendMessage(String folder, MailMessage message)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | A folder to which message is uploaded |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A message to upload |

**Returns:**
java.lang.String - An uri of created message
### appendMessage(String folder, MailMessage message, boolean markAsSent) {#appendMessage-java.lang.String-com.aspose.email.MailMessage-boolean-}
```
public final String appendMessage(String folder, MailMessage message, boolean markAsSent)
```


Uploads the mail message to the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | An uri of folder to which message is uploaded |
| message | [MailMessage](../../com.aspose.email/mailmessage) | A message to upload |
| markAsSent | boolean | A value indicating whether the message should be appended as a sent message or a draft. |

**Returns:**
java.lang.String - An uri of created message
### listMessagesByOption(String folder, int maxNumberOfMessages, int options) {#listMessagesByOption-java.lang.String-int-int-}
```
public ExchangeMessageInfoCollection listMessagesByOption(String folder, int maxNumberOfMessages, int options)
```


List the messages in the specified folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder Uri |
| maxNumberOfMessages | int | Maximum number of messages |
| options | int | Specifies the settings of listing |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A collection of message info
### fetchAttachment(String attachmentUri) {#fetchAttachment-java.lang.String-}
```
public final Attachment fetchAttachment(String attachmentUri)
```


Fetches the attachment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachmentUri | java.lang.String | The attachment uri. (Attachment uri can be retrieved using ListMessages(folder, ExchangeListMessagesOptions.FetchAttachmentInformation) method) |

**Returns:**
[Attachment](../../com.aspose.email/attachment) - [Attachment](../../com.aspose.email/attachment) that represents fetched attachment
### backup(ExchangeFolderInfoCollection folders, String fileName, int options) {#backup-com.aspose.email.ExchangeFolderInfoCollection-java.lang.String-int-}
```
public final void backup(ExchangeFolderInfoCollection folders, String fileName, int options)
```


Backups the content of the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to backup |
| fileName | java.lang.String | A path to the presonal storage file |
| options | int | A backup options |

### backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options) {#backup-com.aspose.email.ExchangeFolderInfoCollection-java.io.OutputStream-int-}
```
public final void backup(ExchangeFolderInfoCollection folders, OutputStream stream, int options)
```


Backups the content of the specified folders

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to backup |
| stream | java.io.OutputStream | A stream to write into |
| options | int | A backup options |

### backupInternal(ExchangeFolderInfoCollection folders, System.IO.Stream stream, int options) {#backupInternal-com.aspose.email.ExchangeFolderInfoCollection-com.aspose.ms.System.IO.Stream-int-}
```
public void backupInternal(ExchangeFolderInfoCollection folders, System.IO.Stream stream, int options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) |  |
| stream | com.aspose.ms.System.IO.Stream |  |
| options | int |  |

### getFolderInfo(String folderUri) {#getFolderInfo-java.lang.String-}
```
public final ExchangeFolderInfo getFolderInfo(String folderUri)
```


Gets the folder information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | A folder uri. |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) - A [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) that represents the folder information.
### folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder) {#folderExists-java.lang.String-java.lang.String-com.aspose.email.ExchangeFolderInfo---}
```
public final boolean folderExists(String parentFolderUri, String folderName, ExchangeFolderInfo[] folder)
```


Checks whether the specified folder exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| folderName | java.lang.String | A folder name. |
| folder | com.aspose.email.ExchangeFolderInfo[] | A [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) that represents the found folder information, if folder exists. |

**Returns:**
boolean - \`\`\` true \`\`\` if the specified folder exists in the specified parent folder; otherwise, \`\`\` false \`\`\`.
### createFolder(String parentFolderUri, String name) {#createFolder-java.lang.String-java.lang.String-}
```
public ExchangeFolderInfo createFolder(String parentFolderUri, String name)
```


Creates the new folder with the specified name in the specified parent folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| name | java.lang.String | A name of folder to be created. |

**Returns:**
[ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo)
### deleteFolder(String folderUri) {#deleteFolder-java.lang.String-}
```
public final void deleteFolder(String folderUri)
```


Deletes the folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The folder Uri |

### restore(String fileName, int options) {#restore-java.lang.String-int-}
```
public final void restore(String fileName, int options)
```


Restores exchange folders from the specified personal storage file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A path to personal storage file. |
| options | int | Restore options. |

### restore(InputStream stream, int options) {#restore-java.io.InputStream-int-}
```
public final void restore(InputStream stream, int options)
```


Restores exchange folders from the given personal storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing personal storage. |
| options | int | Restore options. |

### restoreInternal(System.IO.Stream stream, int options) {#restoreInternal-com.aspose.ms.System.IO.Stream-int-}
```
public void restoreInternal(System.IO.Stream stream, int options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| options | int |  |

### restore(PersonalStorage pst, int options) {#restore-com.aspose.email.PersonalStorage-int-}
```
public final void restore(PersonalStorage pst, int options)
```


Restores exchange folders from the given personal storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | A personal storage containing the backuped imap folders. |
| options | int | Restore options. |

### restore(String fileName, ExchangeFolderInfoCollection folders, int options) {#restore-java.lang.String-com.aspose.email.ExchangeFolderInfoCollection-int-}
```
public final void restore(String fileName, ExchangeFolderInfoCollection folders, int options)
```


Restores the specified exchange folders from the specified personal storage file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | A path to personal storage file. |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to be restored. |
| options | int | Restore options. |

### restore(InputStream stream, ExchangeFolderInfoCollection folders, int options) {#restore-java.io.InputStream-com.aspose.email.ExchangeFolderInfoCollection-int-}
```
public final void restore(InputStream stream, ExchangeFolderInfoCollection folders, int options)
```


Restores the specified exchange folders from the given personal storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream containing personal storage. |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to be restored. |
| options | int | Restore options. |

### restoreInternal(System.IO.Stream stream, ExchangeFolderInfoCollection folders, int options) {#restoreInternal-com.aspose.ms.System.IO.Stream-com.aspose.email.ExchangeFolderInfoCollection-int-}
```
public void restoreInternal(System.IO.Stream stream, ExchangeFolderInfoCollection folders, int options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) |  |
| options | int |  |

### restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, int options) {#restore-com.aspose.email.PersonalStorage-com.aspose.email.ExchangeFolderInfoCollection-int-}
```
public final void restore(PersonalStorage pst, ExchangeFolderInfoCollection folders, int options)
```


Restores the specified exchange folders from the given personal storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | A personal storage containing the backuped exchange folders. |
| folders | [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) | A folders to be restored. |
| options | int | Restore options. |

### createContact(Contact contact) {#createContact-com.aspose.email.Contact-}
```
public final String createContact(Contact contact)
```


Creates a contact item in the Exchange store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | Contact item |

**Returns:**
java.lang.String - The contact Uri
### deleteContact(Contact contact) {#deleteContact-com.aspose.email.Contact-}
```
public final void deleteContact(Contact contact)
```


Deletes the contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [Contact](../../com.aspose.email/contact) | Contact |

### deleteContact(MapiContact contact) {#deleteContact-com.aspose.email.MapiContact-}
```
public final void deleteContact(MapiContact contact)
```


Deletes the contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contact | [MapiContact](../../com.aspose.email/mapicontact) | Contact |

### deleteContact(String id) {#deleteContact-java.lang.String-}
```
public final void deleteContact(String id)
```


Deletes the contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The contact identifier. |

### getContacts(String folderUri) {#getContacts-java.lang.String-}
```
public final Contact[] getContacts(String folderUri)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The URI of folder |

**Returns:**
com.aspose.email.Contact[] - An array of read [Contact](../../com.aspose.email/contact) that represents contact information
### listContacts(String folderUri) {#listContacts-java.lang.String-}
```
public final MapiContact[] listContacts(String folderUri)
```


Lists contacts located in the specified folder on server

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | java.lang.String | The URI of folder |

**Returns:**
com.aspose.email.MapiContact[] - An array of read [MapiContact](../../com.aspose.email/mapicontact) that represents contact information
### resolveContacts(String unresolvedEntry) {#resolveContacts-java.lang.String-}
```
public final Contact[] resolveContacts(String unresolvedEntry)
```


Resolves ambiguous mailbox display names. Note: the maximum count of returned contacts is 100. This is a restriction of used exchange command.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unresolvedEntry | java.lang.String | A name of contact to resolve. |

**Returns:**
com.aspose.email.Contact[] - An array of [Contact](../../com.aspose.email/contact) objects.
### listMailboxes() {#listMailboxes--}
```
public final MapiContactCollection listMailboxes()
```


Lists mailboxes in the global address list.

**Returns:**
[MapiContactCollection](../../com.aspose.email/mapicontactcollection) - A [MapiContactCollection](../../com.aspose.email/mapicontactcollection) that represents contact information.
### getMailboxes() {#getMailboxes--}
```
public final Contact[] getMailboxes()
```


Lists mailboxes in the global address list.

**Returns:**
com.aspose.email.Contact[] - An array of [Contact](../../com.aspose.email/contact) objects.
### listSubFolders(ExchangeFolderInfo parentFolder) {#listSubFolders-com.aspose.email.ExchangeFolderInfo-}
```
public final ExchangeFolderInfoCollection listSubFolders(ExchangeFolderInfo parentFolder)
```


Gets collection of child public folders from parent

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) | The parent [ExchangeFolderInfo](../../com.aspose.email/exchangefolderinfo) |

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) - [ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection) that contains subfolders from the parent folder
### listMessages(String folder) {#listMessages-java.lang.String-}
```
public final ExchangeMessageInfoCollection listMessages(String folder)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessages(String folder, int maxNumberOfMessages) {#listMessages-java.lang.String-int-}
```
public final ExchangeMessageInfoCollection listMessages(String folder, int maxNumberOfMessages)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| maxNumberOfMessages | int | Maximum number of messages |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A [ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages) {#listMessagesByMaxNumberOfMessages-java.lang.String-int-}
```
public final ExchangeMessageInfoCollection listMessagesByMaxNumberOfMessages(String folder, int maxNumberOfMessages)
```


Lists the messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder. |
| maxNumberOfMessages | int | Maximum number of messages |

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection) - A \`\`\` ExchangeMessageInfoCollection \`\`\`
### folderExists(String parentFolderUri, String folderName) {#folderExists-java.lang.String-java.lang.String-}
```
public final boolean folderExists(String parentFolderUri, String folderName)
```


Checks whether the specified folder exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentFolderUri | java.lang.String | An uri of parent folder. |
| folderName | java.lang.String | A folder name. |

**Returns:**
boolean - \`\`\` true \`\`\` if the specified folder exists in the specified parent folder; otherwise, \`\`\` false \`\`\`.
