---
title: CalendarException
second_title: Aspose.Tasks für .NET-API-Referenz
description: Stellt außergewöhnliche Zeiträume in einem Kalender dar.
type: docs
weight: 240
url: /de/net/aspose.tasks/calendarexception/
---
## CalendarException class

Stellt außergewöhnliche Zeiträume in einem Kalender dar.

```csharp
public sealed class CalendarException
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CalendarException](calendarexception)() | Initialisiert eine neue Instanz von[`CalendarException`](../calendarexception) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DaysOfWeek](../../aspose.tasks/calendarexception/daysofweek) { get; } | Ruft die DayTypeCollection für dieses Objekt ab. Die Wochentage, an denen die Ausnahme gültig ist. |
| [DayWorking](../../aspose.tasks/calendarexception/dayworking) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der angegebene Datums- oder Tagestyp funktioniert. |
| [EnteredByOccurrences](../../aspose.tasks/calendarexception/enteredbyoccurrences) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Wiederholungsbereich durch Eingabe einer Anzahl von Vorkommen definiert wird. False gibt an, dass der Wiederholungsbereich durch Eingabe eines Enddatums definiert wird. |
| [FromDate](../../aspose.tasks/calendarexception/fromdate) { get; set; } | Ruft den Beginn der Ausnahmezeit ab oder legt ihn fest. |
| [Month](../../aspose.tasks/calendarexception/month) { get; set; } | Ruft den Monat ab oder legt ihn fest, für den eine Ausnahmewiederholung geplant ist. |
| [MonthDay](../../aspose.tasks/calendarexception/monthday) { get; set; } | Ruft den Tag eines Monats ab oder legt ihn fest, an dem eine Ausnahmewiederholung geplant ist. |
| [MonthItem](../../aspose.tasks/calendarexception/monthitem) { get; set; } | Ruft das Monatselement ab oder legt es fest, für das eine Ausnahmewiederholung geplant ist. |
| [MonthPosition](../../aspose.tasks/calendarexception/monthposition) { get; set; } | Ruft die Position eines Monatselements innerhalb eines Monats ab oder legt sie fest. |
| [Name](../../aspose.tasks/calendarexception/name) { get; set; } | Ruft den Namen der Ausnahme ab oder legt ihn fest. |
| [Occurrences](../../aspose.tasks/calendarexception/occurrences) { get; set; } | Ruft die Anzahl der Vorkommen ab oder legt sie fest, für die die Kalenderausnahme gültig ist. |
| [ParentCalendar](../../aspose.tasks/calendarexception/parentcalendar) { get; } | Ruft den übergeordneten Kalender für dieses Objekt ab. |
| [Period](../../aspose.tasks/calendarexception/period) { get; set; } | Ruft den Wiederholungszeitraum für die Ausnahme ab oder legt ihn fest. |
| [ToDate](../../aspose.tasks/calendarexception/todate) { get; set; } | Ruft das Ende der Ausnahmezeit ab oder legt es fest. |
| [Type](../../aspose.tasks/calendarexception/type) { get; set; } | Ruft den Ausnahmetyp ab oder legt ihn fest. |
| [WorkingTimes](../../aspose.tasks/calendarexception/workingtimes) { get; set; } | Ruft das WorkingTimeCollection-Objekt ab oder setzt es. Die Sammlung von Arbeitszeiten, die die Arbeitszeit am Wochentag definiert.  Mindestens eine Arbeitszeit muss vorhanden sein, mehr als fünf dürfen es nicht sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CheckException](../../aspose.tasks/calendarexception/checkexception)(DateTime) | Gibt wahr zurück, wenn die angegebene Instanz vonDateTime struct ist der Ausnahmetag. |
| [Delete](../../aspose.tasks/calendarexception/delete)() | Löscht die Ausnahmeinstanz aus dem CalendarExceptionCollection-Objekt des übergeordneten Kalenders. |
| [GetExceptionDates](../../aspose.tasks/calendarexception/getexceptiondates)() | Gibt Datumsangaben zurück, an denen die Kalenderausnahme gilt. |
| [GetWorkingTime](../../aspose.tasks/calendarexception/getworkingtime)() | Gibt die Arbeitszeit für eine Kalenderausnahme zurück. |

### Siehe auch

* namensraum [Aspose.Tasks](../../aspose.tasks)
* Montage [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
