---
title: NthOccurrence
second_title: Aspose.Email for .NET API Reference
description: Gets or sets the nth occurrence of the day of the week.
type: docs
weight: 40
url: /net/aspose.email.calendar.recurrences/byday/nthoccurrence/
---
## ByDay.NthOccurrence property

Gets or sets the nth occurrence of the day of the week.

```csharp
public int NthOccurrence { get; set; }
```

### Remarks

Valid range for this property is from -53 to 53.

Positive values represent Nth occurrence from the beginning of the period, for example NthOccurrence = 1, represents 1st occurrence of the day of the week.

Negative values represent Nth occurrence from the end of the period, for example NthOccurrence = -1, represents last occurrence of the day of the week.

When NthOccurrence is zero, it represents all occurrences of the specified day of the week. For example, BYDAY=MO has NthOccurrence zero and represents all Mondays in the set.

### See Also

* class [ByDay](../../byday)
* namespace [Aspose.Email.Calendar.Recurrences](../../byday)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
