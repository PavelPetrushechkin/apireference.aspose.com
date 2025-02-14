---
title: ProjectServerCredentials
second_title: Aspose.Tasks für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonProjectServerCredentialsaspose.tasks/projectservercredentials Klasse die die URL der SharePoint-Site und ein gültiges SPOIDCRL-Autorisierungstoken für die PWA-Site Project Web Access von SharePoint verwendet.
type: docs
weight: 10
url: /de/net/aspose.tasks/projectservercredentials/projectservercredentials/
---
## ProjectServerCredentials(string, string) {#constructor_1}

Initialisiert eine neue Instanz von[`ProjectServerCredentials`](../../projectservercredentials) Klasse, die die URL der SharePoint-Site und ein gültiges SPOIDCRL-Autorisierungstoken für die PWA-Site (Project Web Access) von SharePoint verwendet.

```csharp
public ProjectServerCredentials(string siteUrl, string authToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| siteUrl | String | Die URL der PWA-API (Project Web Access) von Project Online. |
| authToken | String | Das Autorisierungstoken (SPOIDCRL) für die PWA-Website (Project Web Access) von SharePoint. |

### Bemerkungen

Verwenden Sie diesen Konstruktor, um eine Verbindung mit ProjectOnline herzustellen, wenn Sie bereits über AuthToken für Ihre SharePoint Online-Website verfügen.

### Siehe auch

* class [ProjectServerCredentials](../../projectservercredentials)
* namensraum [Aspose.Tasks](../../projectservercredentials)
* Montage [Aspose.Tasks](../../../)

---

## ProjectServerCredentials(string, string, string) {#constructor_2}

Initialisiert eine neue Instanz von[`ProjectServerCredentials`](../../projectservercredentials) Klasse mit URL der SharePoint-Site, Benutzername und Passwort.

```csharp
public ProjectServerCredentials(string siteUrl, string userName, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| siteUrl | String | Die URL der PWA-API (Project Web Access) von Project Online. |
| userName | String | Der Benutzername für die SharePoint-Website. |
| password | String | Das Kennwort für die SharePoint-Website. |

### Bemerkungen

Verwenden Sie diesen Konstruktor, um eine Verbindung mit ProjectOnline herzustellen. Bitte beachten Sie, dass die Legacy-Authentifizierung in Ihrem Azure-Portal und Office 365 Admin Center aktiviert sein sollte.

### Siehe auch

* class [ProjectServerCredentials](../../projectservercredentials)
* namensraum [Aspose.Tasks](../../projectservercredentials)
* Montage [Aspose.Tasks](../../../)

---

## ProjectServerCredentials(string, NetworkCredential) {#constructor}

Initialisiert eine neue Instanz von[`ProjectServerCredentials`](../../projectservercredentials) Klasse, die die URL des Project Web Access-Endpunkts und Netzwerkanmeldeinformationen verwendet.

```csharp
public ProjectServerCredentials(string siteUrl, NetworkCredential credentials)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| siteUrl | String | Die URL des Webzugriffsendpunkts des Projekts. |
| credentials | NetworkCredential | Die Anmeldeinformationen, die für die Anmeldung beim Project Web Access-Endpunkt verwendet werden. |

### Bemerkungen

Verwenden Sie diesen Konstruktor, um über PWA eine Verbindung mit einer lokalen Instanz von Project Server herzustellen.

### Beispiele

In diesem Beispiel ist die Instanz von[`ProjectServerManager`](../../projectservermanager)Klasse wird verwendet, um eine Projektliste aus der Project Server-Instanz zu lesen, die sich unter http://project_server_instance.local befindet.

```csharp
string site = "http://project_server_instance.local/sites/pwa";
var windowsCredentials = new NetworkCredential("Administrator", "my_password", "DOMAIN");
var projectServerCredentials = new ProjectServerCredentials(site, windowsCredentials);
ProjectServerManager manager = new ProjectServerManager(projectServerCredentials);

var list = manager.GetProjectList();
foreach (var projectInfo in list)
{
    Console.WriteLine("{0} - {1} - {2}", projectInfo.Id, projectInfo.CreatedDate, projectInfo.Name);
}
```

### Siehe auch

* class [ProjectServerCredentials](../../projectservercredentials)
* namensraum [Aspose.Tasks](../../projectservercredentials)
* Montage [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
