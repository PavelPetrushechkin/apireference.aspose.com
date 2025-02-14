---
title: CreateNewProject
second_title: Aspose.Tasks für .NET-API-Referenz
description: Erstellt ein neues Projekt in der Project ServerProject Online-Instanz unter Verwendung der Standardspeicheroptionen.
type: docs
weight: 30
url: /de/net/aspose.tasks/projectservermanager/createnewproject/
---
## CreateNewProject(Project) {#createnewproject}

Erstellt ein neues Projekt in der Project Server\Project Online-Instanz unter Verwendung der Standardspeicheroptionen.

```csharp
public void CreateNewProject(Project project)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| project | Project | Das Projekt, das in der Project Server\Project Online-Instanz gespeichert werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [ProjectOnlineException](../../projectonlineexception) | Im Falle eines Kommunikationsfehlers oder eines von einem Server zurückgegebenen Fehlers. |

### Beispiele

In diesem Beispiel wird das Projekt aus einer .mpp-Datei geladen und im Project Online-Konto gespeichert.

```csharp
[C#]
var credentials = new ProjectServerCredentials("https://xxxxxx.sharepoint.com", "yyyyy@xxxxxxx.onmicrosoft.com", "Kennwort");
var project = new Project(@"sample.mpp");
ProjectServerManager manager = new ProjectServerManager(credentials);
manager.CreateNewProject(project);
```

### Siehe auch

* class [Project](../../project)
* class [ProjectServerManager](../../projectservermanager)
* namensraum [Aspose.Tasks](../../projectservermanager)
* Montage [Aspose.Tasks](../../../)

---

## CreateNewProject(Project, ProjectServerSaveOptions) {#createnewproject_1}

Erstellt ein neues Projekt in der Project Server\Project Online-Instanz unter Verwendung der angegebenen Speicheroptionen.

```csharp
public void CreateNewProject(Project project, ProjectServerSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| project | Project | Das Projekt, das in der Project Server\Project Online-Instanz gespeichert werden soll. |
| saveOptions | ProjectServerSaveOptions | Instanz von[`ProjectServerSaveOptions`](../../projectserversaveoptions) Klasse. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [ProjectOnlineException](../../projectonlineexception) | Im Falle eines Kommunikationsfehlers oder eines von einem Server zurückgegebenen Fehlers. |

### Beispiele

In diesem Beispiel wird das Projekt aus einer .mpp-Datei geladen und im Project Online-Konto gespeichert.

```csharp
[C#]
var credentials = new ProjectServerCredentials("https://xxxxxx.sharepoint.com", "yyyyy@xxxxxxx.onmicrosoft.com", "Kennwort");
var project = new Project(@"sample.mpp");
ProjectServerManager manager = new ProjectServerManager(credentials);
manager.CreateNewProject(project, new ProjectServerSaveOptions
{
    ProjectName = "My new project"
});
```

### Siehe auch

* class [Project](../../project)
* class [ProjectServerSaveOptions](../../projectserversaveoptions)
* class [ProjectServerManager](../../projectservermanager)
* namensraum [Aspose.Tasks](../../projectservermanager)
* Montage [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
