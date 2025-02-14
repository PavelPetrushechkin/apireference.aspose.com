---
title: CalendarException
second_title: Aspose.Tasks for .NET API Referansı
description: Bir takvimdeki istisnai dönemleri temsil eder.
type: docs
weight: 240
url: /tr/net/aspose.tasks/calendarexception/
---
## CalendarException class

Bir takvimdeki istisnai dönemleri temsil eder.

```csharp
public sealed class CalendarException
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CalendarException](calendarexception)() | Yeni bir örneğini başlatır[`CalendarException`](../calendarexception) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DaysOfWeek](../../aspose.tasks/calendarexception/daysofweek) { get; } | Bu nesne için DayTypeCollection'ı alır. Özel durumun geçerli olduğu haftanın günleri. |
| [DayWorking](../../aspose.tasks/calendarexception/dayworking) { get; set; } | Belirtilen tarih veya gün türünün çalışıp çalışmadığını gösteren bir değer alır veya ayarlar. |
| [EnteredByOccurrences](../../aspose.tasks/calendarexception/enteredbyoccurrences) { get; set; } | Yinelenme aralığının bir dizi tekrar girilerek tanımlanıp tanımlanmadığını gösteren bir değer alır veya ayarlar. False, yineleme aralığının bir bitiş tarihi girilerek tanımlandığını belirtir. |
| [FromDate](../../aspose.tasks/calendarexception/fromdate) { get; set; } | Özel durum zamanının başlangıcını alır veya ayarlar. |
| [Month](../../aspose.tasks/calendarexception/month) { get; set; } | Bir istisna yinelenmesinin planlandığı ayı alır veya ayarlar. |
| [MonthDay](../../aspose.tasks/calendarexception/monthday) { get; set; } | Bir istisna yinelenmesinin planlandığı bir ayın gününü alır veya ayarlar. |
| [MonthItem](../../aspose.tasks/calendarexception/monthitem) { get; set; } | Bir istisna yinelenmesinin planlandığı ay öğesini alır veya ayarlar. |
| [MonthPosition](../../aspose.tasks/calendarexception/monthposition) { get; set; } | Bir ay içindeki bir ay öğesinin konumunu alır veya ayarlar. |
| [Name](../../aspose.tasks/calendarexception/name) { get; set; } | Özel durumun adını alır veya ayarlar. |
| [Occurrences](../../aspose.tasks/calendarexception/occurrences) { get; set; } | Takvim istisnasının geçerli olduğu tekrarların sayısını alır veya ayarlar. |
| [ParentCalendar](../../aspose.tasks/calendarexception/parentcalendar) { get; } | Bu nesne için üst takvimi alır. |
| [Period](../../aspose.tasks/calendarexception/period) { get; set; } | Özel durum için yinelenme dönemini alır veya ayarlar. |
| [ToDate](../../aspose.tasks/calendarexception/todate) { get; set; } | Özel durum zamanının sonunu alır veya ayarlar. |
| [Type](../../aspose.tasks/calendarexception/type) { get; set; } | Özel durum türünü alır veya ayarlar. |
| [WorkingTimes](../../aspose.tasks/calendarexception/workingtimes) { get; set; } | WorkingTimeCollection nesnesini alır veya ayarlar. Hafta içi çalışılan zamanı tanımlayan çalışma süreleri koleksiyonu.  En az bir çalışma süresi bulunmalıdır ve beşten fazla olamaz. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CheckException](../../aspose.tasks/calendarexception/checkexception)(DateTime) | Belirtilen örnek ise true döndürür.DateTime struct istisna gündür. |
| [Delete](../../aspose.tasks/calendarexception/delete)() | İstisna örneğini üst takvim CalendarExceptionCollection nesnesinden siler. |
| [GetExceptionDates](../../aspose.tasks/calendarexception/getexceptiondates)() | Takvim istisnasının geçerli olduğu tarihleri döndürür. |
| [GetWorkingTime](../../aspose.tasks/calendarexception/getworkingtime)() | Bir takvim istisnası için çalışma süresini döndürür. |

### Ayrıca bakınız

* ad alanı [Aspose.Tasks](../../aspose.tasks)
* toplantı [Aspose.Tasks](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
