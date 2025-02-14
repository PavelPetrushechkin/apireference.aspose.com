---
title: Recalculate
second_title: Справочник по Aspose.Tasks для .NET API
description: Перепланирует все идентификаторы задач проекта уровни структуры даты начала/окончания устанавливает ранние/поздние даты вычисляет резервы поля работы и затрат.
type: docs
weight: 340
url: /ru/net/aspose.tasks/project/recalculate/
---
## Recalculate() {#recalculate}

Перепланирует все идентификаторы задач проекта, уровни структуры, даты начала/окончания, устанавливает ранние/поздние даты, вычисляет резервы, поля работы и затрат.

```csharp
public void Recalculate()
```

### Смотрите также

* class [Project](../../project)
* пространство имен [Aspose.Tasks](../../project)
* сборка [Aspose.Tasks](../../../)

---

## Recalculate(bool) {#recalculate_1}

Перепланирует все идентификаторы задач проекта, уровни структуры, даты начала/окончания, устанавливает ранние/поздние даты, рассчитывает резервы, поля работы и затрат с дополнительной проверкой.

```csharp
public void Recalculate(bool validate)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| validate | Boolean | Если true, будет выполнена проверка пересчета. Какие данные проверяются: На данный момент реализована только базовая проверка диапазонов дат задачи и ссылки на задачу. Диапазоны дат задачи (например, ActualStart - ActualFinish, EarlyStart - EarlyFinish и т. д. ), а также даты ссылок на задачи будут проверяться на соответствие критериям даты, согласно которым дата начала меньше или равна дате окончания. Если какое-либо из условий, описанных выше, не выполняется, то[`RecalculationValidationException`](../../recalculationvalidationexception) будет брошен. |

### Смотрите также

* class [Project](../../project)
* пространство имен [Aspose.Tasks](../../project)
* сборка [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
