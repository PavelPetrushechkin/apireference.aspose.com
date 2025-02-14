---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: Represents properties of a presentation.
type: docs
weight: 5230
url: /net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Properties

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Returns or sets the template of a application. Read/write String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Returns the app version. Read-only String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Returns or sets the author of a presentation. Read/write String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Returns or sets the category of a presentation. Read/write String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Returns or sets the comments of a presentation. Read/write String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Returns or sets the company property. Read/write String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Returns or sets the content status of a presentation. Read/write String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Returns or sets the content type of a presentation. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Returns the number of custom properties actually contained in a collection. Read-only Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Returns the date when a presentation was created. Read/write DateTime. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Returns or sets the HyperlinkBase document property. Read/write String. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Returns or sets the custom property associated with a specified name. Read/write Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Returns or sets the keywords of a presentation. Read/write String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Returns the date when a presentation was printed last time. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Returns or sets the name of a last person who modified a presentation. Read/write String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Returns the date when a presentation was modified last time. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Please see the example in [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) method summary. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Returns or sets the manager property. Read/write String. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Returns or sets the name of the application. Read/write String. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Returns or sets the intended format of a presentation. Read/write String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Returns or sets the presentation revision number. Read/write Int32. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determines whether the presentation is shared between multiple people. Read/write Boolean. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Returns or sets the subject of a presentation. Read/write String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Returns or sets the title of a presentation. Read/write String. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Total editing time of a presentation. Read/write TimeSpan. |

## Methods

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Clears and sets default values for all builtIn properties. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Removes all custom properties. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Check presents of a custom property with a specified name. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Return a custom property name at the specified index. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Gets a named boolean value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Gets a named DateTime value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Gets a named double value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Gets a named float value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Gets a named integer value from the custom properties. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Gets a named string value from the custom properties. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Remove a custom property associated with a specified name. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Sets a named boolean custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Sets a named DateTime custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Sets a named double custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Sets a named float custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Sets a named integer custom property. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Sets a named string custom property. |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
