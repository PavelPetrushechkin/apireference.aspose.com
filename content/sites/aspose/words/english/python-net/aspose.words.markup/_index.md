﻿---
title: aspose.words.markup module
second_title: Aspose.Words for Python via .NET API Reference
description: "The aspose.words.markup module contains classes that represent customer defined semantics in a document: smart tags, custom XML and structured document tags (content controls)."
type: docs
weight: 150
url: /python-net/aspose.words.markup/
---

The **aspose.words.markup** module contains classes that
represent customer defined semantics in a document: smart tags, custom XML and
structured document tags (content controls).




## Classes

| Class | Description |
| --- | --- |
| [CustomPart](./custompart/) | Represents a custom (arbitrary content) part, that is not defined by the ISO/IEC 29500 standard. |
| [CustomPartCollection](./custompartcollection/) | Represents a collection of [CustomPart](./custompart/) objects. |
| [CustomXmlPart](./customxmlpart/) | Represents a Custom XML Data Storage Part (custom XML data within a package). |
| [CustomXmlPartCollection](./customxmlpartcollection/) | Represents a collection of Custom XML Parts. The items are [CustomXmlPart](./customxmlpart/) objects. |
| [CustomXmlProperty](./customxmlproperty/) | Represents a single custom XML attribute or a smart tag property. |
| [CustomXmlPropertyCollection](./customxmlpropertycollection/) | Represents a collection of custom XML attributes or smart tag properties. |
| [CustomXmlSchemaCollection](./customxmlschemacollection/) | A collection of strings that represent XML schemas that are associated with a custom XML part. |
| [IStructuredDocumentTag](./istructureddocumenttag/) | Interface to define a common data for [StructuredDocumentTag](./structureddocumenttag/) and [StructuredDocumentTagRangeStart](./structureddocumenttagrangestart/). |
| [SdtListItem](./sdtlistitem/) | This element specifies a single list item within a parent [SdtType.COMBO_BOX](./sdttype/#COMBO_BOX) or [SdtType.DROP_DOWN_LIST](./sdttype/#DROP_DOWN_LIST) structured document tag. |
| [SdtListItemCollection](./sdtlistitemcollection/) | Provides access to [SdtListItem](./sdtlistitem/) elements of a structured document tag. |
| [SmartTag](./smarttag/) | This element specifies the presence of a smart tag around one or more inline structures (runs, images, fields,etc.) within a paragraph. |
| [StructuredDocumentTag](./structureddocumenttag/) | Represents a structured document tag (SDT or content control) in a document. |
| [StructuredDocumentTagCollection](./structureddocumenttagcollection/) | A collection of [IStructuredDocumentTag](./istructureddocumenttag/) instances that represent the structured document tags in the specified range. |
| [StructuredDocumentTagRangeEnd](./structureddocumenttagrangeend/) | Represents an end of **ranged** structured document tag which accepts multi-sections content. See also [StructuredDocumentTagRangeStart](./structureddocumenttagrangestart/) node. |
| [StructuredDocumentTagRangeStart](./structureddocumenttagrangestart/) | Represents a start of **ranged** structured document tag which accepts multi-sections content. See also [StructuredDocumentTagRangeEnd](./structureddocumenttagrangeend/). |
| [XmlMapping](./xmlmapping/) | Specifies the information that is used to establish a mapping between the parent structured document tag and an XML element stored within a custom XML data part in the document. |

## Enumerations

| Enumeration | Description |
| --- | --- |
| [MarkupLevel](./markuplevel/) | Specifies the level in the document tree where a particular [StructuredDocumentTag](./structureddocumenttag/) can occur. |
| [SdtAppearance](./sdtappearance/) | Specifies the appearance of a structured document tag. |
| [SdtCalendarType](./sdtcalendartype/) | Specifies the possible types of calendars which can be used to specify [StructuredDocumentTag.calendar_type](./structureddocumenttag/calendar_type/) in an Office Open XML document. |
| [SdtDateStorageFormat](./sdtdatestorageformat/) | Specifies how the date for a date SDT is stored/retrieved when the SDT is bound to an XML node in the document's data store. |
| [SdtType](./sdttype/) | Specifies the type of a structured document tag (SDT) node. |

