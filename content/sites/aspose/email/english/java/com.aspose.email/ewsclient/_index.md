---
title: EWSClient
second_title: Aspose.Email for Java API Reference
description:  Provides access to MS Exchange Server by using Exchange Web Services EWS.
type: docs
weight: 163
url: /java/com.aspose.email/ewsclient/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.ExchangeClientBase](../../com.aspose.email/exchangeclientbase)
```
public abstract class EWSClient extends ExchangeClientBase
```

Provides access to MS Exchange Server by using Exchange Web Services (EWS).
## Fields

| Field | Description |
| --- | --- |
| [RootFolderServerNotifications](#RootFolderServerNotifications) | Occurs when arises specified event type for Root folder. |
| [CalendarFolderServerNotifications](#CalendarFolderServerNotifications) | Occurs when arises specified event type for Calendar folder. |
| [ContactsFolderServerNotifications](#ContactsFolderServerNotifications) | Occurs when arises specified event type for Contacts folder. |
| [DeletedItemsFolderServerNotifications](#DeletedItemsFolderServerNotifications) | Occurs when arises specified event type for DeletedItems folder. |
| [DraftsFolderServerNotifications](#DraftsFolderServerNotifications) | Occurs when arises specified event type for Drafts folder. |
| [InboxFolderServerNotifications](#InboxFolderServerNotifications) | Occurs when arises specified event type for Inbox folder. |
| [JournalFolderServerNotifications](#JournalFolderServerNotifications) | Occurs when arises specified event type for Journal folder. |
| [NotesFolderServerNotifications](#NotesFolderServerNotifications) | Occurs when arises specified event type for Notes folder. |
| [OutboxFolderServerNotifications](#OutboxFolderServerNotifications) | Occurs when arises specified event type for Outbox folder. |
| [SentItemsFolderServerNotifications](#SentItemsFolderServerNotifications) | Occurs when arises specified event type for SentItems folder. |
| [TasksFolderServerNotifications](#TasksFolderServerNotifications) | Occurs when arises specified event type for Tasks folder. |
## Methods

| Method | Description |
| --- | --- |
| [useSAAJAPI(boolean value)](#useSAAJAPI-boolean-) | Sets value indicating whether SAAJ is used. |
| [disableSAAJCertificateValidation()](#disableSAAJCertificateValidation--) | Disable SAAJ certificate validation |
| [getEWSClient(URL mailboxUrl)](#getEWSClient-java.net.URL-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(URL mailboxUrl, int serverVersion)](#getEWSClient-java.net.URL-int-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, String domain)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-int-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-int-boolean-java.lang.String-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout)](#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-int-) | Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class |
| [getNotificationTimeout()](#getNotificationTimeout--) | getNotificationTimeout. |
| [setNotificationTimeout(int value)](#setNotificationTimeout-int-) | setNotificationTimeout. |
| [getNotificationsCheckInterval()](#getNotificationsCheckInterval--) | getNotificationsCheckInterval. |
| [setNotificationsCheckInterval(int value)](#setNotificationsCheckInterval-int-) | setNotificationsCheckInterval. |
| [getRootFolderEventFilter()](#getRootFolderEventFilter--) | getRootFolderEventFilter. |
| [setRootFolderEventFilter(int value)](#setRootFolderEventFilter-int-) | setRootFolderEventFilter. |
| [getCalendarFolderEventFilter()](#getCalendarFolderEventFilter--) | getCalendarFolderEventFilter. |
| [setCalendarFolderEventFilter(int value)](#setCalendarFolderEventFilter-int-) | setCalendarFolderEventFilter. |
| [getContactsFolderEventFilter()](#getContactsFolderEventFilter--) | getContactsFolderEventFilter. |
| [setContactsFolderEventFilter(int value)](#setContactsFolderEventFilter-int-) | setContactsFolderEventFilter. |
| [getDeletedItemsFolderEventFilter()](#getDeletedItemsFolderEventFilter--) | getDeletedItemsFolderEventFilter. |
| [setDeletedItemsFolderEventFilter(int value)](#setDeletedItemsFolderEventFilter-int-) | setDeletedItemsFolderEventFilter. |
| [getDraftsFolderEventFilter()](#getDraftsFolderEventFilter--) | getDraftsFolderEventFilter. |
| [setDraftsFolderEventFilter(int value)](#setDraftsFolderEventFilter-int-) | setDraftsFolderEventFilter. |
| [getInboxFolderEventFilter()](#getInboxFolderEventFilter--) | getInboxFolderEventFilter. |
| [setInboxFolderEventFilter(int value)](#setInboxFolderEventFilter-int-) | setInboxFolderEventFilter. |
| [getJournalFolderEventFilter()](#getJournalFolderEventFilter--) | getJournalFolderEventFilter. |
| [setJournalFolderEventFilter(int value)](#setJournalFolderEventFilter-int-) | setJournalFolderEventFilter. |
| [getNotesFolderEventFilter()](#getNotesFolderEventFilter--) | getNotesFolderEventFilter. |
| [setNotesFolderEventFilter(int value)](#setNotesFolderEventFilter-int-) | setNotesFolderEventFilter. |
| [getOutboxFolderEventFilter()](#getOutboxFolderEventFilter--) | getOutboxFolderEventFilter. |
| [setOutboxFolderEventFilter(int value)](#setOutboxFolderEventFilter-int-) | setOutboxFolderEventFilter. |
| [getSentItemsFolderEventFilter()](#getSentItemsFolderEventFilter--) | getSentItemsFolderEventFilter. |
| [setSentItemsFolderEventFilter(int value)](#setSentItemsFolderEventFilter-int-) | setSentItemsFolderEventFilter. |
| [getTasksFolderEventFilter()](#getTasksFolderEventFilter--) | getTasksFolderEventFilter. |
| [setTasksFolderEventFilter(int value)](#setTasksFolderEventFilter-int-) | setTasksFolderEventFilter. |
| [dispose()](#dispose--) |  |
### RootFolderServerNotifications {#RootFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> RootFolderServerNotifications
```


Occurs when arises specified event type for Root folder.

### CalendarFolderServerNotifications {#CalendarFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> CalendarFolderServerNotifications
```


Occurs when arises specified event type for Calendar folder.

### ContactsFolderServerNotifications {#ContactsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> ContactsFolderServerNotifications
```


Occurs when arises specified event type for Contacts folder.

### DeletedItemsFolderServerNotifications {#DeletedItemsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> DeletedItemsFolderServerNotifications
```


Occurs when arises specified event type for DeletedItems folder.

### DraftsFolderServerNotifications {#DraftsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> DraftsFolderServerNotifications
```


Occurs when arises specified event type for Drafts folder.

### InboxFolderServerNotifications {#InboxFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> InboxFolderServerNotifications
```


Occurs when arises specified event type for Inbox folder.

### JournalFolderServerNotifications {#JournalFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> JournalFolderServerNotifications
```


Occurs when arises specified event type for Journal folder.

### NotesFolderServerNotifications {#NotesFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> NotesFolderServerNotifications
```


Occurs when arises specified event type for Notes folder.

### OutboxFolderServerNotifications {#OutboxFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> OutboxFolderServerNotifications
```


Occurs when arises specified event type for Outbox folder.

### SentItemsFolderServerNotifications {#SentItemsFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> SentItemsFolderServerNotifications
```


Occurs when arises specified event type for SentItems folder.

### TasksFolderServerNotifications {#TasksFolderServerNotifications}
```
public final Event<System.EventHandler<ServerNotificationEventArgs>> TasksFolderServerNotifications
```


Occurs when arises specified event type for Tasks folder.

### useSAAJAPI(boolean value) {#useSAAJAPI-boolean-}
```
public static void useSAAJAPI(boolean value)
```


Sets value indicating whether SAAJ is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | True if SAAJ API should be used. |

### disableSAAJCertificateValidation() {#disableSAAJCertificateValidation--}
```
public static void disableSAAJCertificateValidation()
```


Disable SAAJ certificate validation

### getEWSClient(URL mailboxUrl) {#getEWSClient-java.net.URL-}
```
public static IEWSClient getEWSClient(URL mailboxUrl)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUrl | java.net.URL | The URL of mailbox |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(URL mailboxUrl, int serverVersion) {#getEWSClient-java.net.URL-int-}
```
public static IEWSClient getEWSClient(URL mailboxUrl, int serverVersion)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUrl | java.net.URL | The URL of mailbox |
| serverVersion | int | Exchange server versions |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, String domain) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, String domain)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| domain | java.lang.String | The domain name |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, String username, String password, String domain, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| username | java.lang.String | The username |
| password | java.lang.String | The password |
| domain | java.lang.String | The domain name |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-int-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(int serverVersion, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverVersion | int | Exchange server versions |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-int-boolean-java.lang.String-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(int serverVersion, boolean formbasedAuthenticationRequired, String formbasedAuthenticationLocation, String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serverVersion | int | Exchange server versions |
| formbasedAuthenticationRequired | boolean | Set true if form-based authentication is required, otherwise set false. |
| formbasedAuthenticationLocation | java.lang.String | url for form-based authentication |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout) {#getEWSClient-java.lang.String-com.aspose.ms.System.Net.ICredentials-com.aspose.ms.System.Net.WebProxy-int-}
```
public static IEWSClient getEWSClient(String mailboxUri, System.Net.ICredentials credentials, System.Net.WebProxy proxy, int timeout)
```


Initializes a new instance of the [EWSClient](../../com.aspose.email/ewsclient) based class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailboxUri | java.lang.String | The URI of mailbox |
| credentials | com.aspose.ms.System.Net.ICredentials | Contains the credentials for authentication. |
| proxy | com.aspose.ms.System.Net.WebProxy | Contains HTTP proxy settings |
| timeout | int | Sets the number of milliseconds to wait before the operation times out. |

**Returns:**
[IEWSClient](../../com.aspose.email/iewsclient) - Instance of the class based on the [EWSClient](../../com.aspose.email/ewsclient) class.
### getNotificationTimeout() {#getNotificationTimeout--}
```
public int getNotificationTimeout()
```


getNotificationTimeout.

**Returns:**
int - a int.
### setNotificationTimeout(int value) {#setNotificationTimeout-int-}
```
public void setNotificationTimeout(int value)
```


setNotificationTimeout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getNotificationsCheckInterval() {#getNotificationsCheckInterval--}
```
public int getNotificationsCheckInterval()
```


getNotificationsCheckInterval.

**Returns:**
int - a int.
### setNotificationsCheckInterval(int value) {#setNotificationsCheckInterval-int-}
```
public void setNotificationsCheckInterval(int value)
```


setNotificationsCheckInterval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getRootFolderEventFilter() {#getRootFolderEventFilter--}
```
public int getRootFolderEventFilter()
```


getRootFolderEventFilter.

**Returns:**
int - a int.
### setRootFolderEventFilter(int value) {#setRootFolderEventFilter-int-}
```
public void setRootFolderEventFilter(int value)
```


setRootFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getCalendarFolderEventFilter() {#getCalendarFolderEventFilter--}
```
public int getCalendarFolderEventFilter()
```


getCalendarFolderEventFilter.

**Returns:**
int - a int.
### setCalendarFolderEventFilter(int value) {#setCalendarFolderEventFilter-int-}
```
public void setCalendarFolderEventFilter(int value)
```


setCalendarFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getContactsFolderEventFilter() {#getContactsFolderEventFilter--}
```
public int getContactsFolderEventFilter()
```


getContactsFolderEventFilter.

**Returns:**
int - a int.
### setContactsFolderEventFilter(int value) {#setContactsFolderEventFilter-int-}
```
public void setContactsFolderEventFilter(int value)
```


setContactsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getDeletedItemsFolderEventFilter() {#getDeletedItemsFolderEventFilter--}
```
public int getDeletedItemsFolderEventFilter()
```


getDeletedItemsFolderEventFilter.

**Returns:**
int - a int.
### setDeletedItemsFolderEventFilter(int value) {#setDeletedItemsFolderEventFilter-int-}
```
public void setDeletedItemsFolderEventFilter(int value)
```


setDeletedItemsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getDraftsFolderEventFilter() {#getDraftsFolderEventFilter--}
```
public int getDraftsFolderEventFilter()
```


getDraftsFolderEventFilter.

**Returns:**
int - a int.
### setDraftsFolderEventFilter(int value) {#setDraftsFolderEventFilter-int-}
```
public void setDraftsFolderEventFilter(int value)
```


setDraftsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getInboxFolderEventFilter() {#getInboxFolderEventFilter--}
```
public int getInboxFolderEventFilter()
```


getInboxFolderEventFilter.

**Returns:**
int - a int.
### setInboxFolderEventFilter(int value) {#setInboxFolderEventFilter-int-}
```
public void setInboxFolderEventFilter(int value)
```


setInboxFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getJournalFolderEventFilter() {#getJournalFolderEventFilter--}
```
public int getJournalFolderEventFilter()
```


getJournalFolderEventFilter.

**Returns:**
int - a int.
### setJournalFolderEventFilter(int value) {#setJournalFolderEventFilter-int-}
```
public void setJournalFolderEventFilter(int value)
```


setJournalFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getNotesFolderEventFilter() {#getNotesFolderEventFilter--}
```
public int getNotesFolderEventFilter()
```


getNotesFolderEventFilter.

**Returns:**
int - a int.
### setNotesFolderEventFilter(int value) {#setNotesFolderEventFilter-int-}
```
public void setNotesFolderEventFilter(int value)
```


setNotesFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getOutboxFolderEventFilter() {#getOutboxFolderEventFilter--}
```
public int getOutboxFolderEventFilter()
```


getOutboxFolderEventFilter.

**Returns:**
int - a int.
### setOutboxFolderEventFilter(int value) {#setOutboxFolderEventFilter-int-}
```
public void setOutboxFolderEventFilter(int value)
```


setOutboxFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getSentItemsFolderEventFilter() {#getSentItemsFolderEventFilter--}
```
public int getSentItemsFolderEventFilter()
```


getSentItemsFolderEventFilter.

**Returns:**
int - a int.
### setSentItemsFolderEventFilter(int value) {#setSentItemsFolderEventFilter-int-}
```
public void setSentItemsFolderEventFilter(int value)
```


setSentItemsFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### getTasksFolderEventFilter() {#getTasksFolderEventFilter--}
```
public int getTasksFolderEventFilter()
```


getTasksFolderEventFilter.

**Returns:**
int - a int.
### setTasksFolderEventFilter(int value) {#setTasksFolderEventFilter-int-}
```
public void setTasksFolderEventFilter(int value)
```


setTasksFolderEventFilter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a int. |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

