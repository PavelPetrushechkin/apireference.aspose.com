---
title: ResourceAssignment
second_title: Référence de l'API Aspose.Tasks pour .NET
description: Représente une affectation de ressource dans un projet.
type: docs
weight: 1490
url: /fr/net/aspose.tasks/resourceassignment/
---
## ResourceAssignment class

Représente une affectation de ressource dans un projet.

```csharp
public class ResourceAssignment : IEquatable<ResourceAssignment>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Baselines](../../aspose.tasks/resourceassignment/baselines) { get; } | Obtient l'objet AssignmentBaselineCollection. La collection de valeurs de base associées à une affectation. |
| [ExtendedAttributes](../../aspose.tasks/resourceassignment/extendedattributes) { get; set; } | Obtient ou définit une instance de la classe ExtendedAttributeCollection pour cet objet. |
| [Guid](../../aspose.tasks/resourceassignment/guid) { get; set; } | Obtient ou définit un identifiant unique pour cette affectation. |
| [ParentProject](../../aspose.tasks/resourceassignment/parentproject) { get; } | Obtient le projet parent pour ce devoir. |
| [Resource](../../aspose.tasks/resourceassignment/resource) { get; set; } | La ressource affectée à une tâche. |
| [Task](../../aspose.tasks/resourceassignment/task) { get; set; } | La tâche à laquelle une ressource est affectée. |
| [TimephasedData](../../aspose.tasks/resourceassignment/timephaseddata) { get; set; } | Obtient ou définit l'instance de[`TimephasedDataCollection`](../timephaseddatacollection) classe contenant des éléments de[`TimephasedData`](./timephaseddata) classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Delete](../../aspose.tasks/resourceassignment/delete)() | Supprime l'affectation de ressource de la collection d'affectations de projet. |
| override [Equals](../../aspose.tasks/resourceassignment/equals#equals_1)(object) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
| [Equals](../../aspose.tasks/resourceassignment/equals#equals)(ResourceAssignment) | Renvoie une valeur indiquant si cette instance est égale à une instance spécifiée du[`ResourceAssignment`](../resourceassignment) classe. |
| [Get&lt;T&gt;](../../aspose.tasks/resourceassignment/get)(Key&lt;T, AsnKey&gt;) | Renvoie la valeur à laquelle la propriété est mappée dans ce conteneur. |
| override [GetHashCode](../../aspose.tasks/resourceassignment/gethashcode)() | Renvoie une valeur de code de hachage pour l'instance du[`ResourceAssignment`](../resourceassignment) classe. |
| [GetTimephasedData](../../aspose.tasks/resourceassignment/gettimephaseddata#gettimephaseddata)(DateTime, DateTime) | Retours[`TimephasedDataCollection`](../timephaseddatacollection) objet avec les instances de[`TimephasedData`](./timephaseddata) classe dans les dates de début et de fin données deAssignmentWork . |
| [GetTimephasedData](../../aspose.tasks/resourceassignment/gettimephaseddata#gettimephaseddata_1)(DateTime, DateTime, TimephasedDataType) | Renvoie l'instance[`TimephasedDataCollection`](../timephaseddatacollection) classe contenant des instances de[`TimephasedData`](./timephaseddata) classe dans les dates de début et de fin données de spécifié[`TimephasedDataType`](../timephaseddatatype) . |
| [MakeTPs](../../aspose.tasks/resourceassignment/maketps)(DateTime, TimeSpan, Calendar, List&lt;TimephasedData&gt;, bool, int) | Génère une liste de données échelonnées dans le temps. |
| [Set&lt;T&gt;](../../aspose.tasks/resourceassignment/set)(Key&lt;T, AsnKey&gt;, T) | Mappe la propriété spécifiée à la valeur spécifiée dans ce conteneur. |
| [SplitTask](../../aspose.tasks/resourceassignment/splittask)(DateTime, DateTime, Calendar) | Divise la tâche en deux parties. |
| [TimephasedDataFromTaskDuration](../../aspose.tasks/resourceassignment/timephaseddatafromtaskduration)(Calendar) | Génère une liste de données échelonnées dans le temps en fonction de la durée de la tâche et de la date de début prévue. |
| override [ToString](../../aspose.tasks/resourceassignment/tostring)() | Renvoie une représentation sous forme de chaîne courte de l'instance du[`ResourceAssignment`](../resourceassignment) class. Les détails exacts de la représentation ne sont pas spécifiés et peuvent être modifiés. |

### Voir également

* espace de noms [Aspose.Tasks](../../aspose.tasks)
* Assemblée [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
