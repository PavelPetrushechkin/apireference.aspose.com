---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email for .NET API Reference
description: Extends the Common schema with the properties specific to Office 365 Advanced Threat Protection and Threat Intelligence data. Office 365 Advanced Threat Protection ATP and Threat Intelligence events are available for Office 365 customers who have an ATP Threat Intelligence or E5 subscription. Each event in the ATP and Threat Intelligence feed corresponds to the URLs clicked by a user in the organization that were detected as malicious at timeofclick based on Office 365 ATP Safe Links protection.
type: docs
weight: 2670
url: /net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Extends the Common schema with the properties specific to Office 365 Advanced Threat Protection and Threat Intelligence data. Office 365 Advanced Threat Protection (ATP) and Threat Intelligence events are available for Office 365 customers who have an ATP, Threat Intelligence, or E5 subscription. Each event in the ATP and Threat Intelligence feed corresponds to the URLs clicked by a user in the organization that were detected as malicious at time-of-click based on Office 365 ATP Safe Links protection.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Constructors

| Name | Description |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Office 365 service from which the URL was clicked (e.g. Mail). Mandatory: Yes |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | This is true if the URL click is blocked by Office 365 ATP Safe Links protection. Mandatory: Yes |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | This is true if the URL block is clicked through (overridden) by the user based on the organization's policies for Office 365 ATP Safe Links protection. Mandatory: Yes |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | The IP address of the device that was used when the activity was logged. The IP address is displayed in either an IPv4 or IPv6 address format. Mandatory: Yes |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | The date and time in Coordinated Universal Time (UTC) when the user performed the activity. Mandatory: Yes |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Unique identifier of an audit record. Mandatory: Yes |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | For SharePoint and OneDrive for Business activity, the full path name of the file or folder accessed by the user. For Exchange admin audit logging, the name of the object that was modified by the cmdlet. Mandatory: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | The name of the user or admin activity. For a description of the most common operations/activities, see Search the audit log in the Office 365 Protection Center. For Exchange admin activity, this property identifies the name of the cmdlet that was run. For Dlp events, this can be "DlpRuleMatch", "DlpRuleUndo" or "DlpInfo", which are described under "DLP schema" below. Mandatory: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | The GUID for your organization's Office 365 tenant. This value will always be the same for your organization, regardless of the Office 365 service in which it occurs. Mandatory: Yes |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | The type of operation indicated by the record. Mandatory: Yes |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indicates whether the action (specified in the Operation property) was successful or not. Possible values are Succeeded, PartiallySucceded, or Failed. For Exchange admin activity, the value is either True or False. Mandatory: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Was this event created by a hosted O365 service or an on-premises server? Possible values are online and onprem. Note that SharePoint is the only workload currently sending events from on-premises to O365. Mandatory: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Identifier for the Office 365 service from which the URL was clicked (e.g. for Mail, this is the Exchange Online Network Message Id). Mandatory: Yes |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | The date and time in Coordinated Universal Time (UTC) when the user clicked the URL. Mandatory: Yes |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL clicked by the user. Mandatory: Yes |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | The UPN (User Principal Name) of the user who performed the action (specified in the Operation property) that resulted in the record being logged; for example, my_name@my_domain_name. Note that records for activity performed by system accounts (such as SHAREPOINT\system or NT AUTHORITY\SYSTEM) are also included. Mandatory: Yes |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | The IP address for the user who clicked the URL. The IP address is displayed in either an IPv4 or IPv6 address format. Mandatory: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | An alternative ID for the user identified in the UserId property. For example, this property is populated with the passport unique ID (PUID) for events performed by users in SharePoint, OneDrive for Business, and Exchange. This property may also specify the same value as the UserID property for events occurring in other services and events performed by system accounts. Mandatory: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | The type of user that performed the operation. Mandatory: Yes |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | The Office 365 service where the activity occurred in the Workload string. The possible values for this property are: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Mandatory: No |

### See Also

* class [Content](../content)
* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
