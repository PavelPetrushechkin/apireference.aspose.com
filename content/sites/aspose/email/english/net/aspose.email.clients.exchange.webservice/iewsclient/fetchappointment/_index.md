---
title: FetchAppointment
second_title: Aspose.Email for .NET API Reference
description: Fetch the specified appointment from server.
type: docs
weight: 710
url: /net/aspose.email.clients.exchange.webservice/iewsclient/fetchappointment/
---
## FetchAppointment(string) {#fetchappointment}

Fetch the specified appointment from server.

```csharp
public Appointment FetchAppointment(string appointmentUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointmentUri | String | An uri of appointment to be fetched. |

### Return Value

A fetched [`Appointment`](../../../aspose.email.calendar/appointment).

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *appointmentUri* is `null` or `empty`. |

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## FetchAppointment(string, string) {#fetchappointment_1}

Fetch the specified appointment from server.

```csharp
public Appointment FetchAppointment(string appointmentUri, string folderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointmentUri | String | An uri of appointment to be fetched. |
| folderUri | String | An uri of appointments parent folder. |

### Return Value

A fetched [`Appointment`](../../../aspose.email.calendar/appointment).

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *appointmentUri* is `null` or `empty`. |

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
