---
title: MailQueryBuilder
second_title: Aspose.Email for Java API Reference
description:  Represents the builder of search expression.
type: docs
weight: 373
url: /java/com.aspose.email/mailquerybuilder/
---
**Inheritance:**
java.lang.Object
```
public class MailQueryBuilder
```

Represents the builder of search expression.

--------------------

Note: By default, the result is the intersection (AND function) of all the messages that match those keys. To join keys by OR function, please, use Or() method of this class
## Constructors

| Constructor | Description |
| --- | --- |
| [MailQueryBuilder()](#MailQueryBuilder--) | Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class. |
| [MailQueryBuilder(Charset defaultEncoding)](#MailQueryBuilder-java.nio.charset.Charset-) | Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [getTo()](#getTo--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field. |
| [getText()](#getText--) | Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message. |
| [getBcc()](#getBcc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field. |
| [getBody()](#getBody--) | Gets the field that allows to find messages that contain the specified string in the body of the message. |
| [getCc()](#getCc--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field. |
| [getFrom()](#getFrom--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field. |
| [getSubject()](#getSubject--) | Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field. |
| [getDefaultEncoding()](#getDefaultEncoding--) | Gets default encoding (charset) for query builder |
| [getInternalDate()](#getInternalDate--) | Gets the field that allows to find messages by internal date. |
| [getSentDate()](#getSentDate--) | Gets the field that allows to find messages by sent date. |
| [or(MailQuery query1, MailQuery query2)](#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-) | Search messages that match either search key. |
| [getQuery()](#getQuery--) | Gets the query. |
### MailQueryBuilder() {#MailQueryBuilder--}
```
public MailQueryBuilder()
```


Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class.

### MailQueryBuilder(Charset defaultEncoding) {#MailQueryBuilder-java.nio.charset.Charset-}
```
public MailQueryBuilder(Charset defaultEncoding)
```


Initializes a new instance of the [MailQueryBuilder](../../com.aspose.email/mailquerybuilder) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| defaultEncoding | java.nio.charset.Charset | Contains default encoding (charset) for query builder. |

### getTo() {#getTo--}
```
public final StringComparisonField getTo()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's TO field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents TO search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getText() {#getText--}
```
public final StringComparisonField getText()
```


Gets the field that allows to find the messages that contain the specified string in the headers (subject, from, to, cc) and body of the message.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents text header or body search fields.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBcc() {#getBcc--}
```
public final StringComparisonField getBcc()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's BCC field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents BCC search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getBody() {#getBody--}
```
public final StringComparisonField getBody()
```


Gets the field that allows to find messages that contain the specified string in the body of the message.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents body search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getCc() {#getCc--}
```
public final StringComparisonField getCc()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's CC field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents cc search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getFrom() {#getFrom--}
```
public final StringComparisonField getFrom()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's FROM field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents from search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getSubject() {#getSubject--}
```
public final StringComparisonField getSubject()
```


Gets the field that allows to find messages that contain the specified string in the envelope structure's SUBJECT field.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents subject search field.

**Returns:**
[StringComparisonField](../../com.aspose.email/stringcomparisonfield)
### getDefaultEncoding() {#getDefaultEncoding--}
```
public final Charset getDefaultEncoding()
```


Gets default encoding (charset) for query builder

**Returns:**
java.nio.charset.Charset
### getInternalDate() {#getInternalDate--}
```
public final DateComparisonField getInternalDate()
```


Gets the field that allows to find messages by internal date.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents internal date search field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### getSentDate() {#getSentDate--}
```
public final DateComparisonField getSentDate()
```


Gets the field that allows to find messages by sent date.

Value: The [DateComparisonField](../../com.aspose.email/datecomparisonfield) that represents sent date search field.

**Returns:**
[DateComparisonField](../../com.aspose.email/datecomparisonfield)
### or(MailQuery query1, MailQuery query2) {#or-com.aspose.email.MailQuery-com.aspose.email.MailQuery-}
```
public MailQuery or(MailQuery query1, MailQuery query2)
```


Search messages that match either search key. Provides disjunction between two expressions (OR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| query1 | [MailQuery](../../com.aspose.email/mailquery) | The query1. |
| query2 | [MailQuery](../../com.aspose.email/mailquery) | The query2. |

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query (one searching criterion).
### getQuery() {#getQuery--}
```
public MailQuery getQuery()
```


Gets the query.

**Returns:**
[MailQuery](../../com.aspose.email/mailquery) - [MailQuery](../../com.aspose.email/mailquery) that represents search query.
