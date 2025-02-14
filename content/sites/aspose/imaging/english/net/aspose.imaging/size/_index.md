---
title: Size
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 11060
url: /net/aspose.imaging/size/
---
## Size structure

Represents size.

```csharp
public struct Size
```

## Constructors

| Name | Description |
| --- | --- |
| [Size](size)(Point) | Initializes a new instance of the [`Size`](../size) structure from the specified [`Point`](../point). |
| [Size](size)(int, int) | Initializes a new instance of the [`Size`](../size) structure from the specified dimensions. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.imaging/size/empty) { get; } | Gets a new instance of the [`Size`](../size) structure that has [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Height](../../aspose.imaging/size/height) { get; set; } | Gets or sets the vertical component of this [`Size`](../size). |
| [IsEmpty](../../aspose.imaging/size/isempty) { get; } | Gets a value indicating whether this [`Size`](../size) has width and height of 0. |
| [Width](../../aspose.imaging/size/width) { get; set; } | Gets or sets the horizontal component of this [`Size`](../size). |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.imaging/size/add)(Size, Size) | Adds the width and height of one [`Size`](../size) structure to the width and height of another [`Size`](../size) structure. |
| static [Ceiling](../../aspose.imaging/size/ceiling)(SizeF) | Converts the specified [`SizeF`](../sizef) structure to a [`Size`](../size) structure by rounding the values of the [`Size`](../size) structure to the next higher integer values. |
| static [Round](../../aspose.imaging/size/round)(SizeF) | Converts the specified [`SizeF`](../sizef) structure to a [`Size`](../size) structure by rounding the values of the [`SizeF`](../sizef) structure to the nearest integer values. |
| static [Subtract](../../aspose.imaging/size/subtract)(Size, Size) | Subtracts the width and height of one [`Size`](../size) structure from the width and height of another [`Size`](../size) structure. |
| static [Truncate](../../aspose.imaging/size/truncate)(SizeF) | Converts the specified [`SizeF`](../sizef) structure to a [`Size`](../size) structure by truncating the values of the [`SizeF`](../sizef) structure to the next lower integer values. |
| override [Equals](../../aspose.imaging/size/equals)(object) | Tests to see whether the specified object is a [`Size`](../size) with the same dimensions as this [`Size`](../size). |
| override [GetHashCode](../../aspose.imaging/size/gethashcode)() | Returns a hash code for this [`Size`](../size) structure. |
| override [ToString](../../aspose.imaging/size/tostring)() | Creates a human-readable string that represents this [`Size`](../size). |
| [operator +](../../aspose.imaging/size/op_addition) | Adds the width and height of one [`Size`](../size) structure to the width and height of another [`Size`](../size) structure. |
| [operator ==](../../aspose.imaging/size/op_equality) | Tests whether two [`Size`](../size) structures are equal. |
| [explicit operator](../../aspose.imaging/size/op_explicit) | Converts the specified [`Size`](../size) to a [`Point`](../point). |
| [implicit operator](../../aspose.imaging/size/op_implicit) | Converts the specified [`Size`](../size) to a [`SizeF`](../sizef). |
| [operator !=](../../aspose.imaging/size/op_inequality) | Tests whether two [`Size`](../size) structures are different. |
| [operator -](../../aspose.imaging/size/op_subtraction) | Subtracts the width and height of one [`Size`](../size) structure from the width and height of another [`Size`](../size) structure. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
