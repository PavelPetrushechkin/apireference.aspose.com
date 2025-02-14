---
title: Notebook
second_title: Aspose.Email for Java API Reference
description:  https//docs.microsoft.com/en-us/graph/api/resources/notebookviewgraph-rest-1.0
 A OneNote notebook.
type: docs
weight: 525
url: /java/com.aspose.email/notebook/
---
**Inheritance:**
java.lang.Object
```
public class Notebook
```

https://docs.microsoft.com/en-us/graph/api/resources/notebook?view=graph-rest-1.0 A OneNote notebook.
## Constructors

| Constructor | Description |
| --- | --- |
| [Notebook()](#Notebook--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCreatedBy()](#getCreatedBy--) | Identity of the user, device, and application which created the item. |
| [getCreatedDateTime()](#getCreatedDateTime--) | The date and time when the notebook was created. |
| [isCreatedDateTimeSpecified()](#isCreatedDateTimeSpecified--) | Indicates whether CreatedDateTime property is specified. |
| [setCreatedDateTimeSpecified(boolean value)](#setCreatedDateTimeSpecified-boolean-) | Indicates whether CreatedDateTime property is specified. |
| [getId()](#getId--) | The unique identifier of the notebook. |
| [isDefault()](#isDefault--) | Indicates whether this is the user's default notebook. |
| [isDefaultSpecified()](#isDefaultSpecified--) | Indicates whether IsDefault property is specified. |
| [setDefaultSpecified(boolean value)](#setDefaultSpecified-boolean-) | Indicates whether IsDefault property is specified. |
| [isShared()](#isShared--) | Indicates whether the notebook is shared. |
| [isSharedSpecified()](#isSharedSpecified--) | Indicates whether IsShared property is specified. |
| [setSharedSpecified(boolean value)](#setSharedSpecified-boolean-) | Indicates whether IsShared property is specified. |
| [getLastModifiedBy()](#getLastModifiedBy--) | Identity of the user, device, and application which created the item. |
| [getLastModifiedDateTime()](#getLastModifiedDateTime--) | The date and time when the notebook was last modified. |
| [isLastModifiedDateTimeSpecified()](#isLastModifiedDateTimeSpecified--) | Indicates whether LastModifiedDateTime property is specified. |
| [setLastModifiedDateTimeSpecified(boolean value)](#setLastModifiedDateTimeSpecified-boolean-) | Indicates whether LastModifiedDateTime property is specified. |
| [getLinks()](#getLinks--) | Links for opening the notebook. |
| [setLinks(NotebookLinks value)](#setLinks-com.aspose.email.NotebookLinks-) | Links for opening the notebook. |
| [getDisplayName()](#getDisplayName--) | The name of the notebook. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | The name of the notebook. |
| [getSectionGroupsUrl()](#getSectionGroupsUrl--) | The URL for the sectionGroups navigation property, which returns all the section groups in the notebook. |
| [getSectionsUrl()](#getSectionsUrl--) | The URL for the sections navigation property, which returns all the sections in the notebook. |
| [getSelf()](#getSelf--) | The endpoint where you can get details about the notebook. |
| [getUserRole()](#getUserRole--) | Possible values are: Owner, Contributor, Reader, None. |
### Notebook() {#Notebook--}
```
public Notebook()
```


### getCreatedBy() {#getCreatedBy--}
```
public final IdentitySet getCreatedBy()
```


Identity of the user, device, and application which created the item. Read-only.

**Returns:**
[IdentitySet](../../com.aspose.email/identityset)
### getCreatedDateTime() {#getCreatedDateTime--}
```
public final System.DateTimeOffset getCreatedDateTime()
```


The date and time when the notebook was created. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Read-only.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### isCreatedDateTimeSpecified() {#isCreatedDateTimeSpecified--}
```
public final boolean isCreatedDateTimeSpecified()
```


Indicates whether CreatedDateTime property is specified.

**Returns:**
boolean
### setCreatedDateTimeSpecified(boolean value) {#setCreatedDateTimeSpecified-boolean-}
```
public final void setCreatedDateTimeSpecified(boolean value)
```


Indicates whether CreatedDateTime property is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getId() {#getId--}
```
public final String getId()
```


The unique identifier of the notebook. Read-only.

**Returns:**
java.lang.String
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indicates whether this is the user's default notebook. Read-only.

**Returns:**
boolean
### isDefaultSpecified() {#isDefaultSpecified--}
```
public final boolean isDefaultSpecified()
```


Indicates whether IsDefault property is specified.

**Returns:**
boolean
### setDefaultSpecified(boolean value) {#setDefaultSpecified-boolean-}
```
public final void setDefaultSpecified(boolean value)
```


Indicates whether IsDefault property is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isShared() {#isShared--}
```
public final System.Nullable<Boolean> isShared()
```


Indicates whether the notebook is shared. If true, the contents of the notebook can be seen by people other than the owner. Read-only.

**Returns:**
com.aspose.ms.System.Nullable<java.lang.Boolean>
### isSharedSpecified() {#isSharedSpecified--}
```
public final boolean isSharedSpecified()
```


Indicates whether IsShared property is specified.

**Returns:**
boolean
### setSharedSpecified(boolean value) {#setSharedSpecified-boolean-}
```
public final void setSharedSpecified(boolean value)
```


Indicates whether IsShared property is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastModifiedBy() {#getLastModifiedBy--}
```
public final IdentitySet getLastModifiedBy()
```


Identity of the user, device, and application which created the item. Read-only.

**Returns:**
[IdentitySet](../../com.aspose.email/identityset)
### getLastModifiedDateTime() {#getLastModifiedDateTime--}
```
public final System.DateTimeOffset getLastModifiedDateTime()
```


The date and time when the notebook was last modified. The timestamp represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'. Read-only.

**Returns:**
com.aspose.ms.System.DateTimeOffset
### isLastModifiedDateTimeSpecified() {#isLastModifiedDateTimeSpecified--}
```
public final boolean isLastModifiedDateTimeSpecified()
```


Indicates whether LastModifiedDateTime property is specified.

**Returns:**
boolean
### setLastModifiedDateTimeSpecified(boolean value) {#setLastModifiedDateTimeSpecified-boolean-}
```
public final void setLastModifiedDateTimeSpecified(boolean value)
```


Indicates whether LastModifiedDateTime property is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinks() {#getLinks--}
```
public final NotebookLinks getLinks()
```


Links for opening the notebook. The oneNoteClientURL link opens the notebook in the OneNote native client if it's installed. The oneNoteWebURL link opens the notebook in OneNote on the web.

**Returns:**
[NotebookLinks](../../com.aspose.email/notebooklinks)
### setLinks(NotebookLinks value) {#setLinks-com.aspose.email.NotebookLinks-}
```
public final void setLinks(NotebookLinks value)
```


Links for opening the notebook. The oneNoteClientURL link opens the notebook in the OneNote native client if it's installed. The oneNoteWebURL link opens the notebook in OneNote on the web.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NotebookLinks](../../com.aspose.email/notebooklinks) |  |

### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


The name of the notebook.

**Returns:**
java.lang.String
### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


The name of the notebook.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionGroupsUrl() {#getSectionGroupsUrl--}
```
public final String getSectionGroupsUrl()
```


The URL for the sectionGroups navigation property, which returns all the section groups in the notebook. Read-only.

**Returns:**
java.lang.String
### getSectionsUrl() {#getSectionsUrl--}
```
public final String getSectionsUrl()
```


The URL for the sections navigation property, which returns all the sections in the notebook. Read-only.

**Returns:**
java.lang.String
### getSelf() {#getSelf--}
```
public final String getSelf()
```


The endpoint where you can get details about the notebook. Read-only.

**Returns:**
java.lang.String
### getUserRole() {#getUserRole--}
```
public final int getUserRole()
```


Possible values are: Owner, Contributor, Reader, None. Owner represents owner-level access to the notebook. Contributor represents read/write access to the notebook. Reader represents read-only access to the notebook. Read-only.

**Returns:**
int
