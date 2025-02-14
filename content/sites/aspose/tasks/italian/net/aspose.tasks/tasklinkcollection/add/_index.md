---
title: Add
second_title: Riferimento all'API di Aspose.Tasks per .NET
description: Restituisce unistanza di Finish-StartTaskLinkaspose.tasks/tasklink che è stato aggiunto alloggetto TaskLinkCollection.
type: docs
weight: 40
url: /it/net/aspose.tasks/tasklinkcollection/add/
---
## Add(Task, Task) {#add}

Restituisce un'istanza di Finish-Start[`TaskLink`](../../tasklink) che è stato aggiunto all'oggetto TaskLinkCollection.

```csharp
public TaskLink Add(Task pred, Task succ)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pred | Task | Compito predecessore. |
| succ | Task | Compito successivo. |

### Valore di ritorno

un'istanza di collegamento attività che è stata aggiunta a questo oggetto.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Se una qualsiasi delle attività di input è uguale a null, alloraArgumentNullException sarà lanciato. |

### Guarda anche

* class [TaskLink](../../tasklink)
* class [Task](../../task)
* class [TaskLinkCollection](../../tasklinkcollection)
* spazio dei nomi [Aspose.Tasks](../../tasklinkcollection)
* assemblea [Aspose.Tasks](../../../)

---

## Add(Task, Task, TaskLinkType) {#add_1}

Restituisce un'istanza di[`TaskLink`](../../tasklink) che è stato aggiunto all'oggetto TaskLinkCollection.

```csharp
public TaskLink Add(Task pred, Task succ, TaskLinkType linkType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pred | Task | Compito predecessore. |
| succ | Task | Compito successivo. |
| linkType | TaskLinkType | Tipo di collegamento[`TaskLinkType`](../../tasklinktype) |

### Valore di ritorno

un'istanza di collegamento attività che è stata aggiunta a questo oggetto.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Se una qualsiasi delle attività di input è uguale a null, alloraArgumentNullException sarà lanciato. |

### Guarda anche

* class [TaskLink](../../tasklink)
* class [Task](../../task)
* enum [TaskLinkType](../../tasklinktype)
* class [TaskLinkCollection](../../tasklinkcollection)
* spazio dei nomi [Aspose.Tasks](../../tasklinkcollection)
* assemblea [Aspose.Tasks](../../../)

---

## Add(Task, Task, TaskLinkType, Duration) {#add_2}

Restituisce un'istanza di[`TaskLink`](../../tasklink) che è stato aggiunto all'oggetto TaskLinkCollection.

```csharp
public TaskLink Add(Task pred, Task succ, TaskLinkType linkType, Duration lag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pred | Task | Compito predecessore. |
| succ | Task | Compito successivo. |
| linkType | TaskLinkType | Tipo di collegamento[`TaskLinkType`](../../tasklinktype) |
| lag | Duration | Ritardo di collegamento[`Duration`](../../duration). |

### Valore di ritorno

un collegamento attività che è stato aggiunto a questo oggetto.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Se una qualsiasi delle attività di input è uguale a null, alloraArgumentNullException sarà lanciato. |

### Guarda anche

* class [TaskLink](../../tasklink)
* class [Task](../../task)
* enum [TaskLinkType](../../tasklinktype)
* struct [Duration](../../duration)
* class [TaskLinkCollection](../../tasklinkcollection)
* spazio dei nomi [Aspose.Tasks](../../tasklinkcollection)
* assemblea [Aspose.Tasks](../../../)

---

## Add(TaskLink) {#add_3}

Questa è l'implementazione stub del metodo Add di ICollection, che genera solo NotSupportedException

```csharp
public void Add(TaskLink item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | TaskLink | L'elemento da aggiungere. |

### Guarda anche

* class [TaskLink](../../tasklink)
* class [TaskLinkCollection](../../tasklinkcollection)
* spazio dei nomi [Aspose.Tasks](../../tasklinkcollection)
* assemblea [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
