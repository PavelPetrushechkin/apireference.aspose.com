---
title: MessageObjectAttachmentEntity
second_title: Aspose.Email for Java API Reference
description:  Represents an attachment entity.
type: docs
weight: 495
url: /java/com.aspose.email/messageobjectattachmententity/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObjectAttachmentEntity implements IMessageObjectPropertyContainer
```

Represents an attachment entity.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageObjectAttachmentEntity()](#MessageObjectAttachmentEntity--) | Initializes a new instance of the [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) class. |
## Methods

| Method | Description |
| --- | --- |
| [getProperties()](#getProperties--) | Gets the attachment properties. |
| [getEmbeddedMessage()](#getEmbeddedMessage--) | Gets or sets the Embedded Message Object storage if present.Can be null. |
| [setEmbeddedMessage(MessageObject value)](#setEmbeddedMessage-com.aspose.email.MessageObject-) | Gets or sets the Embedded Message Object storage if present.Can be null. |
| [getCustomAttachmentStorageData()](#getCustomAttachmentStorageData--) | Gets or sets the custom attachment storage data.Can be null. |
| [setCustomAttachmentStorageData(CustomAttachmentStorage value)](#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-) | Gets or sets the custom attachment storage data.Can be null. |
### MessageObjectAttachmentEntity() {#MessageObjectAttachmentEntity--}
```
public MessageObjectAttachmentEntity()
```


Initializes a new instance of the [MessageObjectAttachmentEntity](../../com.aspose.email/messageobjectattachmententity) class.

### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Gets the attachment properties.

Value: The properties collection.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
### getEmbeddedMessage() {#getEmbeddedMessage--}
```
public final MessageObject getEmbeddedMessage()
```


Gets or sets the Embedded Message Object storage if present.Can be null.

Value: The embedded message.

--------------------

Mutually exclusive with \`\`\` MessageObjectAttachmentEntity.CustomAttachmentStorageData \`\`\`(\#getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage)) or both can be null.

**Returns:**
[MessageObject](../../com.aspose.email/messageobject)
### setEmbeddedMessage(MessageObject value) {#setEmbeddedMessage-com.aspose.email.MessageObject-}
```
public final void setEmbeddedMessage(MessageObject value)
```


Gets or sets the Embedded Message Object storage if present.Can be null.

Value: The embedded message.

--------------------

Mutually exclusive with \`\`\` MessageObjectAttachmentEntity.CustomAttachmentStorageData \`\`\`(\#getCustomAttachmentStorageData/\#setCustomAttachmentStorageData(CustomAttachmentStorage)) or both can be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MessageObject](../../com.aspose.email/messageobject) |  |

### getCustomAttachmentStorageData() {#getCustomAttachmentStorageData--}
```
public final CustomAttachmentStorage getCustomAttachmentStorageData()
```


Gets or sets the custom attachment storage data.Can be null.

Value: The custom attachment storage data.

--------------------

Mutually exclusive with \`\`\` MessageObjectAttachmentEntity.EmbeddedMessage \`\`\`(\#getEmbeddedMessage/\#setEmbeddedMessage(MessageObject)) or both can be null.

**Returns:**
[CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage)
### setCustomAttachmentStorageData(CustomAttachmentStorage value) {#setCustomAttachmentStorageData-com.aspose.email.CustomAttachmentStorage-}
```
public final void setCustomAttachmentStorageData(CustomAttachmentStorage value)
```


Gets or sets the custom attachment storage data.Can be null.

Value: The custom attachment storage data.

--------------------

Mutually exclusive with \`\`\` MessageObjectAttachmentEntity.EmbeddedMessage \`\`\`(\#getEmbeddedMessage/\#setEmbeddedMessage(MessageObject)) or both can be null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CustomAttachmentStorage](../../com.aspose.email/customattachmentstorage) |  |

