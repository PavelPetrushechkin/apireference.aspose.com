---
title: ParentStyle
second_title: Référence de l'API Aspose.Tasks pour .NET
description: Obtient ou définit le style parent ou commun pour le style personnalisé spécifique à la tâche.
type: docs
weight: 160
url: /fr/net/aspose.tasks.visualization/ganttbarstyle/parentstyle/
---
## GanttBarStyle.ParentStyle property

Obtient ou définit le style parent (ou commun) pour le style personnalisé spécifique à la tâche.

```csharp
public GanttBarStyle ParentStyle { get; set; }
```

### Remarques

La tâche peut avoir plusieurs styles personnalisés avec différents styles parents. Par exemple, considérez une tâche ayant un style personnalisé avec un style parent "Critique" et un autre style avec un style parent "Normal". En termes simples, si la tâche est critique, le premier style est appliqué. Si la tâche devient non critique, le second style est appliqué (cette logique est héritée de Microsoft Project Professional).

### Voir également

* class [GanttBarStyle](../../ganttbarstyle)
* espace de noms [Aspose.Tasks.Visualization](../../ganttbarstyle)
* Assemblée [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
