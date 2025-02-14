---
title: ConnectionAsgmtType
second_title: Aspose.Email for Java API Reference
description:  Defines algorithm of connection allocation in multiple threads environment
type: docs
weight: 113
url: /java/com.aspose.email/connectionasgmttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ConnectionAsgmtType extends System.Enum
```

Defines algorithm of connection allocation in multiple threads environment
## Fields

| Field | Description |
| --- | --- |
| [UseMainOrDefault](#UseMainOrDefault) | This mode uses by default in email clients. |
| [UseMain](#UseMain) | Email client uses main connection for all operations from multiple threads. |
| [UseDefault](#UseDefault) | Email client uses implicitly only default connections for all operations from multiple threads. |
### UseMainOrDefault {#UseMainOrDefault}
```
public static final int UseMainOrDefault
```


This mode uses by default in email clients. Email client uses main connection for all operations from multiple threads if default connection hasn't been created, or connection hasnt been passed as method parameter explicitly. Main connection is connection which is created in the same time like email client. User can create default connections for threads with CreateConnection method. If default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread. If default connection for thread is not created, main connection is used for all methods of email client which are invoked in this thread. User also can create independent connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm because of thread may be reused in this case. To avoid this problem user has to manually dispose default conection (if he uses it) in the end of the code which executes in the thread.

### UseMain {#UseMain}
```
public static final int UseMain
```


Email client uses main connection for all operations from multiple threads. Main connection is connection which is created in the same time like email client. User cann't create default connections. User can create independent connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections.

### UseDefault {#UseDefault}
```
public static final int UseDefault
```


Email client uses implicitly only default connections for all operations from multiple threads. Main connection is not used in this mode. If default connection hasn't been created for some thread (first invocation of email client method), email client creates default connection implicitly for thread before first operation is executed. User can't create default connections for threads with CreateConnection method because they are created automatically. When default connection for thread is created, it's used implicitly for all methods of email client which are invoked in this thread.read. User also can create independent connections not linked with threads (not default connections) with CreateConnection method. If user wants to use other connections (not main and not default) he has to pass this connection explicitly as parameter of a method which he wants to use. User can additionally create any number of connections. Default connection can be only one per thread. Please note default connections works correctly if user uses Thread objects for multitasking programming. If user uses ConnectionPool or uses Task objects for multitasking programming this mode may lead to wrong behaviour of a programm because of thread may be reused in this case. To avoid this problem user has to manually dispose default conection in the end of the code which executes in the thread.

