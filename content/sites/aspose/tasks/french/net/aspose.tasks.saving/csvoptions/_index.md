---
title: CsvOptions
second_title: Référence de l'API Aspose.Tasks pour .NET
description: Permet de spécifier des options supplémentaires lors de lenregistrement du projet au format CSV.
type: docs
weight: 1710
url: /fr/net/aspose.tasks.saving/csvoptions/
---
## CsvOptions class

Permet de spécifier des options supplémentaires lors de l'enregistrement du projet au format CSV.

```csharp
public class CsvOptions : SaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [CsvOptions](csvoptions)() | Initialise une nouvelle instance du[`CsvOptions`](../csvoptions) classe qui peut être utilisée pour enregistrer le projet au format CSV. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BarStyles](../../aspose.tasks.saving/saveoptions/barstyles) { get; set; } | Obtient ou définit la liste des instances du[`BarStyle`](../../aspose.tasks.visualization/barstyle) classe qui apparaissent dans la vue du projet. |
| [CustomPageSize](../../aspose.tasks.saving/saveoptions/custompagesize) { get; set; } | Obtient ou définit la taille de page personnalisée en points (1 point = 1/72 de pouce). |
| [DataCategory](../../aspose.tasks.saving/csvoptions/datacategory) { get; set; } | Obtient ou définit une catégorie de données à enregistrer. |
| [DrawNonWorkingTime](../../aspose.tasks.saving/saveoptions/drawnonworkingtime) { get; set; } | Obtient ou définit une valeur indiquant si les périodes chômées doivent être dessinées (la valeur par défaut est TRUE). |
| [Encoding](../../aspose.tasks.saving/csvoptions/encoding) { get; set; } | Obtient ou définit un encodage pour enregistrer le CSV avec. |
| [EndDate](../../aspose.tasks.saving/saveoptions/enddate) { get; set; } | Obtient ou définit une date à laquelle terminer le rendu. |
| [FitContent](../../aspose.tasks.saving/saveoptions/fitcontent) { get; set; } | Obtient ou définit une valeur indiquant si la hauteur de la ligne doit être augmentée pour s'adapter à son contenu. |
| [Gridlines](../../aspose.tasks.saving/saveoptions/gridlines) { get; set; } | Obtient ou définit une liste de[`Gridline`](../../aspose.tasks.visualization/gridline) qui apparaissent dans la vue du projet. |
| [IncludeHeaders](../../aspose.tasks.saving/csvoptions/includeheaders) { get; set; } | Obtient ou définit une valeur indiquant s'il faut inclure ou non les en-têtes (la valeur par défaut est TRUE). |
| [LegendOnEachPage](../../aspose.tasks.saving/saveoptions/legendoneachpage) { get; set; } | Obtient ou définit une valeur indiquant si la légende doit être affichée sur chaque page (la valeur par défaut est TRUE). |
| [MarkCriticalTasks](../../aspose.tasks.saving/saveoptions/markcriticaltasks) { get; set; } | Obtient ou définit une valeur indiquant si les tâches critiques doivent être affichées en rouge (la valeur par défaut est FALSE). |
| [NonWorkingTimeColor](../../aspose.tasks.saving/saveoptions/nonworkingtimecolor) { get; set; } | Obtient ou définit la couleur des périodes chômées. |
| [PageCount](../../aspose.tasks.saving/saveoptions/pagecount) { get; } | Obtient ou définit le nombre de pages du projet. |
| [PageSize](../../aspose.tasks.saving/saveoptions/pagesize) { get; set; } | Obtient ou définit la taille de la page à afficher (la valeur par défaut est PageSize.A4). |
| [PresentationFormat](../../aspose.tasks.saving/saveoptions/presentationformat) { get; set; } | Obtient ou définit le[`PresentationFormat`](../saveoptions/presentationformat) dans lequel le document sera enregistré. |
| [RenderToSinglePage](../../aspose.tasks.saving/saveoptions/rendertosinglepage) { get; set; } | Obtient ou définit une valeur indiquant si un projet doit être rendu sur une seule page lorsque le projet est enregistré au format graphique. La taille de la page sera modifiée afin que le projet rendu puisse tenir sur une seule page. |
| [RollUpGanttBars](../../aspose.tasks.saving/saveoptions/rollupganttbars) { get; set; } | Obtient ou définit une valeur indiquant si les sous-tâches de la barre des tâches récapitulatives doivent être marquées. Pour les sous-tâches, le champ Cumul indique si les informations sur les barres du Gantt des sous-tâches seront reportées dans la barre des tâches récapitulatives. Pour les tâches récapitulatives, le champ Cumul Le champ indique si la barre des tâches récapitulatives affiche des barres cumulées. Le champ Cumul des tâches récapitulatives doit être défini sur Oui pour que les sous-tâches puissent y être cumulées. |
| [SaveFormat](../../aspose.tasks.saving/saveoptions/saveformat) { get; } | Obtient ou définit le format dans lequel le document sera enregistré si cet objet d'options d'enregistrement est utilisé. |
| [StartDate](../../aspose.tasks.saving/saveoptions/startdate) { get; set; } | Obtient ou définit la date à partir de laquelle le rendu commence. |
| [TasksComparer](../../aspose.tasks.saving/saveoptions/taskscomparer) { get; set; } | Obtient ou définit le comparateur pour trier les tâches sur le diagramme de Gantt et le tableau de la feuille de tâches. |
| [TasksFilter](../../aspose.tasks.saving/saveoptions/tasksfilter) { get; set; } | Obtient ou définit la condition utilisée pour filtrer les tâches rendues sur les diagrammes de Gantt, de feuille de tâches et d'utilisation des tâches. |
| [TextDelimiter](../../aspose.tasks.saving/csvoptions/textdelimiter) { get; set; } | Obtient ou définit un délimiteur de texte. |
| [TextStyles](../../aspose.tasks.saving/saveoptions/textstyles) { get; set; } | Obtient ou définit la liste des instances du[`TextStyle`](../../aspose.tasks.visualization/textstyle) classe qui apparaissent dans la vue du projet. |
| [Timescale](../../aspose.tasks.saving/saveoptions/timescale) { get; set; } | Obtient ou définit le[`Timescale`](../saveoptions/timescale) valeur qui est utilisée pour contrôler la façon dont l'échelle de temps (le cas échéant) est rendue lorsque le projet est enregistré au format graphique. |
| virtual [UseGradientBrush](../../aspose.tasks.saving/saveoptions/usegradientbrush) { get; set; } | Obtient ou définit une valeur indiquant si le pinceau dégradé doit être utilisé lors du rendu du diagramme de Gantt. |
| [View](../../aspose.tasks.saving/saveoptions/view) { get; set; } | Obtient ou définit une liste des colonnes de vue à afficher ([`GanttChartColumn`](../../aspose.tasks.visualization/ganttchartcolumn) ). S'ils ne sont pas définis, les identifiants de tâche, les noms de tâche, le début et la fin sont rendus uniquement. Si à la fois Afficher et[`ViewSettings`](../saveoptions/viewsettings) les propriétés sont définies, les colonnes de View remplacent les colonnes de ViewSettings. |
| [ViewSettings](../../aspose.tasks.saving/saveoptions/viewsettings) { get; set; } | Obtient ou définit une vue ([`View`](../saveoptions/view) rendre. Vous pouvez utiliser ces options pour spécifier explicitement quelle vue doit être enregistrée aux formats PDF, HTML ou Image. Si cette propriété est définie,[`PresentationFormat`](../../aspose.tasks.visualization/presentationformat) La propriété est ignorée lorsque le projet est enregistré. La vue doit provenir de l'un des écrans suivants (([`Screen`](../../aspose.tasks/view/screen) )) : (Gantt, Feuille de tâches, Utilisation des tâches, Feuille de ressources, Utilisation des ressources) |

### Voir également

* class [SaveOptions](../saveoptions)
* espace de noms [Aspose.Tasks.Saving](../../aspose.tasks.saving)
* Assemblée [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
