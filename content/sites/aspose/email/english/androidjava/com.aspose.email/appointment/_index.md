---
title: Appointment
second_title: Aspose.Email for Android via Java API Reference
description:  Represents a calendar to an e-mail.
type: docs
weight: 26
url: /java/com.aspose.email/appointment/
---
**Inheritance:**
java.lang.Object
```
public class Appointment
```

Represents a calendar to an e-mail.

--------------------

> This example demonstrates how to add a calendar to an E-Mail message.
> 
> [Java]
> 
> ```
> MailMessage msg = new MailMessage();
> 
>      //attendees for the event
>      MailAddressCollection attendees = new MailAddressCollection();
>      attendees.add(new MailAddress("person1@domain.com"));
>      attendees.add(new MailAddress("person2@domain.com"));
>      attendees.add(new MailAddress("person3@domain.com"));
> 
>      //create appointment
>      Appointment app = new Appointment("Room 112",
>           new Date(2006,7,17,13,0,0), new Date(2006,7,17,14,0,0),
>           new MailAddress("somebody@domain.com"),
>           attendees );
>      app.setSummary("Release Meetting");
>      app.setDescription("Discuss for the next release");
> 
>      //add calendar to the message
>      msg.addAlternateView(app.requestApointment());
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-) | Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-) | Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-) | Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class. |
| [Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)](#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-) | Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class. |
## Methods

| Method | Description |
| --- | --- |
| [getLocation()](#getLocation--) | Gets or sets the location. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Gets or sets the location. |
| [getAppointmentClass()](#getAppointmentClass--) | Specifies the access classification for the appointment. |
| [setAppointmentClass(int value)](#setAppointmentClass-int-) | Specifies the access classification for the appointment. |
| [getMicrosoftImportance()](#getMicrosoftImportance--) | Specifies the importance of an appointment. |
| [setMicrosoftImportance(int value)](#setMicrosoftImportance-int-) | Specifies the importance of an appointment. |
| [getMicrosoftBusyStatus()](#getMicrosoftBusyStatus--) | Specifies the BUSY status of an appointment. |
| [setMicrosoftBusyStatus(int value)](#setMicrosoftBusyStatus-int-) | Specifies the BUSY status of an appointment. |
| [getMicrosoftIntendedStatus()](#getMicrosoftIntendedStatus--) | Specifies the INTENDED status of an appointment. |
| [setMicrosoftIntendedStatus(int value)](#setMicrosoftIntendedStatus-int-) | Specifies the INTENDED status of an appointment. |
| [getTransparency()](#getTransparency--) | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [setTransparency(int value)](#setTransparency-int-) | Specifies whether or not this appointment is intended to be visible in availability searches. |
| [getStatus()](#getStatus--) | Gets or sets the overall status or confirmation for the object. |
| [setStatus(int value)](#setStatus-int-) | Gets or sets the overall status or confirmation for the object. |
| [getSummary()](#getSummary--) | Gets or sets the summary. |
| [setSummary(String value)](#setSummary-java.lang.String-) | Gets or sets the summary. |
| [getDescription()](#getDescription--) | Gets or sets the description. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Gets or sets the description. |
| [getHtmlDescription()](#getHtmlDescription--) | Gets or sets html representation of description. |
| [setHtmlDescription(String value)](#setHtmlDescription-java.lang.String-) | Gets or sets html representation of description. |
| [isDescriptionHtml()](#isDescriptionHtml--) | Gets or sets value which indicates if description is in HTML format |
| [setDescriptionHtml(boolean value)](#setDescriptionHtml-boolean-) | Gets or sets value which indicates if description is in HTML format |
| [getStartDate()](#getStartDate--) | Gets or sets the start date. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Gets or sets the start date. |
| [getEndDate()](#getEndDate--) | Gets or sets the end date. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Gets or sets the end date. |
| [getCreatedDate()](#getCreatedDate--) | Gets or sets the date and time that calendar information was created. |
| [setCreatedDate(Date value)](#setCreatedDate-java.util.Date-) | Gets or sets the date and time that calendar information was created. |
| [getLastModifiedDate()](#getLastModifiedDate--) | Gets or sets the date and time that calendar information was last revised. |
| [setLastModifiedDate(Date value)](#setLastModifiedDate-java.util.Date-) | Gets or sets the date and time that calendar information was last revised. |
| [getAttendees()](#getAttendees--) | Gets or sets the attendees. |
| [setAttendees(MailAddressCollection value)](#setAttendees-com.aspose.email.MailAddressCollection-) | Gets or sets the attendees. |
| [getOptionalAttendees()](#getOptionalAttendees--) | Gets the optional attendees. |
| [getOrganizer()](#getOrganizer--) | Gets or sets the organizer. |
| [setOrganizer(MailAddress value)](#setOrganizer-com.aspose.email.MailAddress-) | Gets or sets the organizer. |
| [getRecurrence()](#getRecurrence--) | Gets or sets the recurrence pattern. |
| [setRecurrence(RecurrencePattern value)](#setRecurrence-com.aspose.email.RecurrencePattern-) | Gets or sets the recurrence pattern. |
| [getSequenceId()](#getSequenceId--) | Gets the sequence id. |
| [getFlags()](#getFlags--) | Gets or sets appointment flags. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets appointment flags. |
| [getMethodType()](#getMethodType--) | Gets or sets the iCalendar object method type associated with the calendar object. |
| [setMethodType(int value)](#setMethodType-int-) | Gets or sets the iCalendar object method type associated with the calendar object. |
| [getReminders()](#getReminders--) | Contains collection of AppointmentReminder [AppointmentReminder](../../com.aspose.email/appointmentreminder) objects. |
| [getAttachments()](#getAttachments--) | Gets the collection of attachments of appointment. |
| [getStartTimeZone()](#getStartTimeZone--) | Start time zone |
| [setStartTimeZone(String value)](#setStartTimeZone-java.lang.String-) | Start time zone |
| [getEndTimeZone()](#getEndTimeZone--) | End time zone |
| [setEndTimeZone(String value)](#setEndTimeZone-java.lang.String-) | End time zone |
| [resetTimeZone()](#resetTimeZone--) | Set local time zone |
| [setTimeZone(String tzName)](#setTimeZone-java.lang.String-) | Set time zone |
| [requestApointment()](#requestApointment--) | Requests the apointment. |
| [requestApointment(int seqId)](#requestApointment-int-) | Requests the apointment. |
| [cancelAppointment()](#cancelAppointment--) | Cancels the appointment. |
| [cancelAppointment(int seqId)](#cancelAppointment-int-) | Cancels the appointment. |
| [updateAppointment()](#updateAppointment--) | Updates the appointment. |
| [updateAppointment(int seqId)](#updateAppointment-int-) | Updates the appointment. |
| [getAppointmentHtml()](#getAppointmentHtml--) | Gets the calendar HTML. |
| [getAppointmentText()](#getAppointmentText--) | Gets the calendar text. |
| [getAppointmentText(AppointmentFormattingOptions formattingOptions)](#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-) | Gets the calendar text. |
| [save(String filePath)](#save-java.lang.String-) | Saves appointment to the file with iCalendar format using te default save options |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves appointment to the file with specified format using te default save options |
| [save(String filePath, AppointmentSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-) | Saves appointment to the file with specified save options |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves appointment to the file with iCalendar format using te default save options |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves appointment to the stream with specified format using te default save options |
| [save(OutputStream stream, AppointmentSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-) | Saves appointment to the stream with specified save options |
| [load(String filePath)](#load-java.lang.String-) | Loads [Appointment](../../com.aspose.email/appointment) from the file. |
| [load(String filePath, AppointmentLoadOptions options)](#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-) | Loads [Appointment](../../com.aspose.email/appointment) from the file. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads [Appointment](../../com.aspose.email/appointment) from the stream |
| [load(InputStream stream, boolean applyLocalTimeZone)](#load-java.io.InputStream-boolean-) | Loads [Appointment](../../com.aspose.email/appointment) from the stream |
| [load(InputStream stream, AppointmentLoadOptions options)](#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-) | Loads [Appointment](../../com.aspose.email/appointment) from the stream |
| [getUniqueId()](#getUniqueId--) | Gets or sets a string value that contains the GUID for the calendar item. |
| [setUniqueId(String value)](#setUniqueId-java.lang.String-) | Gets or sets a string value that contains the GUID for the calendar item. |
### Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the calendar event. |
| startDate | java.util.Date | The start time of the calendar event. |
| endDate | java.util.Date | The end time of the calendar event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the calendar event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of th calendar event. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees)
```


Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the calendar event. |
| summary | java.lang.String | The summary of the calendar event. |
| description | java.lang.String | The description of the calendar event. |
| startDate | java.util.Date | The start time of the calendar event. |
| endDate | java.util.Date | The end time of the calendar event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the calendar event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of th calendar event. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid)
```


Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the calendar event. |
| summary | java.lang.String | The summary of the calendar event. |
| description | java.lang.String | The description of the calendar event. |
| startDate | java.util.Date | The start time of the calendar event. |
| endDate | java.util.Date | The end time of the calendar event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the calendar event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of th calendar event. |
| uid | java.lang.String | The unique identifier of th calendar event. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, RecurrencePattern recurrencePattern)
```


Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the calendar event. |
| summary | java.lang.String | The summary of the calendar event. |
| description | java.lang.String | The description of the calendar event. |
| startDate | java.util.Date | The start time of the calendar event. |
| endDate | java.util.Date | The end time of the calendar event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the calendar event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of th calendar event. |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | The recurrence pattern. |

### Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern) {#Appointment-java.lang.String-java.lang.String-java.lang.String-java.util.Date-java.util.Date-com.aspose.email.MailAddress-com.aspose.email.MailAddressCollection-java.lang.String-com.aspose.email.RecurrencePattern-}
```
public Appointment(String location, String summary, String description, Date startDate, Date endDate, MailAddress organizer, MailAddressCollection attendees, String uid, RecurrencePattern recurrencePattern)
```


Initialize a new instance of the [Appointment](../../com.aspose.email/appointment) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | java.lang.String | The location of the calendar event. |
| summary | java.lang.String | The summary of the calendar event. |
| description | java.lang.String | The description of the calendar event. |
| startDate | java.util.Date | The start time of the calendar event. |
| endDate | java.util.Date | The end time of the calendar event. |
| organizer | [MailAddress](../../com.aspose.email/mailaddress) | The organizer of the calendar event. |
| attendees | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) | The attendees of th calendar event. |
| uid | java.lang.String | The unique identifier of th calendar event. |
| recurrencePattern | [RecurrencePattern](../../com.aspose.email/recurrencepattern) | The recurrence pattern. |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets or sets the location.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Gets or sets the location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAppointmentClass() {#getAppointmentClass--}
```
public final int getAppointmentClass()
```


Specifies the access classification for the appointment.

**Returns:**
int
### setAppointmentClass(int value) {#setAppointmentClass-int-}
```
public final void setAppointmentClass(int value)
```


Specifies the access classification for the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMicrosoftImportance() {#getMicrosoftImportance--}
```
public final int getMicrosoftImportance()
```


Specifies the importance of an appointment.

**Returns:**
int
### setMicrosoftImportance(int value) {#setMicrosoftImportance-int-}
```
public final void setMicrosoftImportance(int value)
```


Specifies the importance of an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMicrosoftBusyStatus() {#getMicrosoftBusyStatus--}
```
public final int getMicrosoftBusyStatus()
```


Specifies the BUSY status of an appointment.

**Returns:**
int
### setMicrosoftBusyStatus(int value) {#setMicrosoftBusyStatus-int-}
```
public final void setMicrosoftBusyStatus(int value)
```


Specifies the BUSY status of an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMicrosoftIntendedStatus() {#getMicrosoftIntendedStatus--}
```
public final int getMicrosoftIntendedStatus()
```


Specifies the INTENDED status of an appointment.

**Returns:**
int
### setMicrosoftIntendedStatus(int value) {#setMicrosoftIntendedStatus-int-}
```
public final void setMicrosoftIntendedStatus(int value)
```


Specifies the INTENDED status of an appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransparency() {#getTransparency--}
```
public final int getTransparency()
```


Specifies whether or not this appointment is intended to be visible in availability searches.

**Returns:**
int
### setTransparency(int value) {#setTransparency-int-}
```
public final void setTransparency(int value)
```


Specifies whether or not this appointment is intended to be visible in availability searches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets or sets the overall status or confirmation for the object.

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Gets or sets the overall status or confirmation for the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSummary() {#getSummary--}
```
public final String getSummary()
```


Gets or sets the summary.

**Returns:**
java.lang.String
### setSummary(String value) {#setSummary-java.lang.String-}
```
public final void setSummary(String value)
```


Gets or sets the summary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets or sets the description.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Gets or sets the description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHtmlDescription() {#getHtmlDescription--}
```
public final String getHtmlDescription()
```


Gets or sets html representation of description.

**Returns:**
java.lang.String
### setHtmlDescription(String value) {#setHtmlDescription-java.lang.String-}
```
public final void setHtmlDescription(String value)
```


Gets or sets html representation of description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDescriptionHtml() {#isDescriptionHtml--}
```
public final boolean isDescriptionHtml()
```


Gets or sets value which indicates if description is in HTML format

**Returns:**
boolean
### setDescriptionHtml(boolean value) {#setDescriptionHtml-boolean-}
```
public final void setDescriptionHtml(boolean value)
```


Gets or sets value which indicates if description is in HTML format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Gets or sets the start date.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Gets or sets the start date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Gets or sets the end date.

**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Gets or sets the end date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getCreatedDate() {#getCreatedDate--}
```
public final Date getCreatedDate()
```


Gets or sets the date and time that calendar information was created.

Value: The java.util.Date that represents creation date and time.

**Returns:**
java.util.Date
### setCreatedDate(Date value) {#setCreatedDate-java.util.Date-}
```
public final void setCreatedDate(Date value)
```


Gets or sets the date and time that calendar information was created.

Value: The java.util.Date that represents creation date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastModifiedDate() {#getLastModifiedDate--}
```
public final Date getLastModifiedDate()
```


Gets or sets the date and time that calendar information was last revised.

Value: The java.util.Date that represents modification date and time.

**Returns:**
java.util.Date
### setLastModifiedDate(Date value) {#setLastModifiedDate-java.util.Date-}
```
public final void setLastModifiedDate(Date value)
```


Gets or sets the date and time that calendar information was last revised.

Value: The java.util.Date that represents modification date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getAttendees() {#getAttendees--}
```
public final MailAddressCollection getAttendees()
```


Gets or sets the attendees.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### setAttendees(MailAddressCollection value) {#setAttendees-com.aspose.email.MailAddressCollection-}
```
public final void setAttendees(MailAddressCollection value)
```


Gets or sets the attendees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddressCollection](../../com.aspose.email/mailaddresscollection) |  |

### getOptionalAttendees() {#getOptionalAttendees--}
```
public final MailAddressCollection getOptionalAttendees()
```


Gets the optional attendees.

Value: The address collection of optional attendees.

**Returns:**
[MailAddressCollection](../../com.aspose.email/mailaddresscollection)
### getOrganizer() {#getOrganizer--}
```
public final MailAddress getOrganizer()
```


Gets or sets the organizer.

**Returns:**
[MailAddress](../../com.aspose.email/mailaddress)
### setOrganizer(MailAddress value) {#setOrganizer-com.aspose.email.MailAddress-}
```
public final void setOrganizer(MailAddress value)
```


Gets or sets the organizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MailAddress](../../com.aspose.email/mailaddress) |  |

### getRecurrence() {#getRecurrence--}
```
public final RecurrencePattern getRecurrence()
```


Gets or sets the recurrence pattern.

Value: The recurrence pattern.

**Returns:**
[RecurrencePattern](../../com.aspose.email/recurrencepattern)
### setRecurrence(RecurrencePattern value) {#setRecurrence-com.aspose.email.RecurrencePattern-}
```
public final void setRecurrence(RecurrencePattern value)
```


Gets or sets the recurrence pattern.

Value: The recurrence pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RecurrencePattern](../../com.aspose.email/recurrencepattern) |  |

### getSequenceId() {#getSequenceId--}
```
public final String getSequenceId()
```


Gets the sequence id.

Value: The sequence id.

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets or sets appointment flags.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public final void setFlags(int value)
```


Gets or sets appointment flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMethodType() {#getMethodType--}
```
public final int getMethodType()
```


Gets or sets the iCalendar object method type associated with the calendar object.

**Returns:**
int
### setMethodType(int value) {#setMethodType-int-}
```
public final void setMethodType(int value)
```


Gets or sets the iCalendar object method type associated with the calendar object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReminders() {#getReminders--}
```
public final AppointmentReminderCollection getReminders()
```


Contains collection of AppointmentReminder [AppointmentReminder](../../com.aspose.email/appointmentreminder) objects.

**Returns:**
[AppointmentReminderCollection](../../com.aspose.email/appointmentremindercollection)
### getAttachments() {#getAttachments--}
```
public final AttachmentCollection getAttachments()
```


Gets the collection of attachments of appointment.

**Returns:**
[AttachmentCollection](../../com.aspose.email/attachmentcollection)
### getStartTimeZone() {#getStartTimeZone--}
```
public final String getStartTimeZone()
```


Start time zone

**Returns:**
java.lang.String
### setStartTimeZone(String value) {#setStartTimeZone-java.lang.String-}
```
public final void setStartTimeZone(String value)
```


Start time zone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEndTimeZone() {#getEndTimeZone--}
```
public final String getEndTimeZone()
```


End time zone

**Returns:**
java.lang.String
### setEndTimeZone(String value) {#setEndTimeZone-java.lang.String-}
```
public final void setEndTimeZone(String value)
```


End time zone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### resetTimeZone() {#resetTimeZone--}
```
public final void resetTimeZone()
```


Set local time zone

### setTimeZone(String tzName) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String tzName)
```


Set time zone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tzName | java.lang.String | The time zone name, for sample "America/New\_York" |

### requestApointment() {#requestApointment--}
```
public final AlternateView requestApointment()
```


Requests the apointment.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### requestApointment(int seqId) {#requestApointment-int-}
```
public final AlternateView requestApointment(int seqId)
```


Requests the apointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence id. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### cancelAppointment() {#cancelAppointment--}
```
public final AlternateView cancelAppointment()
```


Cancels the appointment.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### cancelAppointment(int seqId) {#cancelAppointment-int-}
```
public final AlternateView cancelAppointment(int seqId)
```


Cancels the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence id. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### updateAppointment() {#updateAppointment--}
```
public final AlternateView updateAppointment()
```


Updates the appointment.

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### updateAppointment(int seqId) {#updateAppointment-int-}
```
public final AlternateView updateAppointment(int seqId)
```


Updates the appointment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| seqId | int | The sequence id. |

**Returns:**
[AlternateView](../../com.aspose.email/alternateview) - AlternateView[AlternateView](../../com.aspose.email/alternateview) that represents the format to view an email message.
### getAppointmentHtml() {#getAppointmentHtml--}
```
public final String getAppointmentHtml()
```


Gets the calendar HTML.

**Returns:**
java.lang.String - String value of calendar as HTML.
### getAppointmentText() {#getAppointmentText--}
```
public final String getAppointmentText()
```


Gets the calendar text.

**Returns:**
java.lang.String - String value of calendar as plain text.
### getAppointmentText(AppointmentFormattingOptions formattingOptions) {#getAppointmentText-com.aspose.email.AppointmentFormattingOptions-}
```
public final String getAppointmentText(AppointmentFormattingOptions formattingOptions)
```


Gets the calendar text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattingOptions | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) | [AppointmentFormattingOptions](../../com.aspose.email/appointmentformattingoptions) that represents appointment formatting options. |

**Returns:**
java.lang.String - The text representation of appointment.
### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves appointment to the file with iCalendar format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves appointment to the file with specified format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |
| saveFormat | int | A save format |

### save(String filePath, AppointmentSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(String filePath, AppointmentSaveOptions saveOptions)
```


Saves appointment to the file with specified save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | A save options |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves appointment to the file with iCalendar format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves appointment to the stream with specified format using te default save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveFormat | int | A save format |

### save(OutputStream stream, AppointmentSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.AppointmentSaveOptions-}
```
public final void save(OutputStream stream, AppointmentSaveOptions saveOptions)
```


Saves appointment to the stream with specified save options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveOptions | [AppointmentSaveOptions](../../com.aspose.email/appointmentsaveoptions) | A save options |

### load(String filePath) {#load-java.lang.String-}
```
public static Appointment load(String filePath)
```


Loads [Appointment](../../com.aspose.email/appointment) from the file. Supported file formats: iCalendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(String filePath, AppointmentLoadOptions options) {#load-java.lang.String-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(String filePath, AppointmentLoadOptions options)
```


Loads [Appointment](../../com.aspose.email/appointment) from the file. Supported file formats: iCalendar

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file path. |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Represents appointment load options[AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions). |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment).
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Appointment load(InputStream stream)
```


Loads [Appointment](../../com.aspose.email/appointment) from the stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to load from |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, boolean applyLocalTimeZone) {#load-java.io.InputStream-boolean-}
```
public static Appointment load(InputStream stream, boolean applyLocalTimeZone)
```


Loads [Appointment](../../com.aspose.email/appointment) from the stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to load from |
| applyLocalTimeZone | boolean | Convert time to local timezone |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### load(InputStream stream, AppointmentLoadOptions options) {#load-java.io.InputStream-com.aspose.email.AppointmentLoadOptions-}
```
public static Appointment load(InputStream stream, AppointmentLoadOptions options)
```


Loads [Appointment](../../com.aspose.email/appointment) from the stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to load from |
| options | [AppointmentLoadOptions](../../com.aspose.email/appointmentloadoptions) | Represents appointment load options |

**Returns:**
[Appointment](../../com.aspose.email/appointment) - A read [Appointment](../../com.aspose.email/appointment)
### getUniqueId() {#getUniqueId--}
```
public final String getUniqueId()
```


Gets or sets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property.

Value: The unique id.

**Returns:**
java.lang.String
### setUniqueId(String value) {#setUniqueId-java.lang.String-}
```
public final void setUniqueId(String value)
```


Gets or sets a string value that contains the GUID for the calendar item. In MS Exchange this is PidLidGlobalObjectId mapi property.

Value: The unique id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

