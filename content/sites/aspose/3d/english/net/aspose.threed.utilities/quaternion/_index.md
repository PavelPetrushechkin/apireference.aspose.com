---
title: Quaternion
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 2590
url: /net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Quaternion is usually used to perform rotation in computer graphics.

```csharp
public struct Quaternion
```

## Constructors

| Name | Description |
| --- | --- |
| [Quaternion](quaternion)(double, double, double, double) | Initializes a new instance of the [`Quaternion`](../quaternion) class. |

## Properties

| Name | Description |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length) { get; } | Gets the length of the quaternion |

## Methods

| Name | Description |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis)(double, Vector3) | Creates a quaternion around given axis and rotate in clockwise |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle)(Vector3) | Creates quaternion from given Euler angle |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle)(double, double, double) | Creates quaternion from given Euler angle |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation)(Vector3, Vector3) | Creates a quaternion that rotate from original to destination direction |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate)(float, Quaternion, Quaternion) | Populates this quaternion with the interpolated value between the given quaternion arguments for a t between from and to. |
| [Concat](../../aspose.threed.utilities/quaternion/concat)(Quaternion) | Concatenate two quaternions |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate)() | Returns a conjugate quaternion of current quaternion |
| [Dot](../../aspose.threed.utilities/quaternion/dot)(Quaternion) | Dots product |
| override [Equals](../../aspose.threed.utilities/quaternion/equals)(object) | Check if two quaternions equals |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles)() | Converts quaternion to rotation represented by Euler angles All components are in radian |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode)() | Gets the hash code of Quaternion |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse)() | Returns a inverse quaternion of current quaternion |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize)() | Normalize the quaternion |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix)() | Convert the rotation presented by quaternion to transform matrix. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring)() | Gets the representation of quaternion in string |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition) | Operator overloading for + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division) | Operator overloading for / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality) | Equal operator for quaternion |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality) | Not-equal operator for quaternion |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply) | Operator overloading for * (5 operators) |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity) | The Identity quaternion. |
| [w](../../aspose.threed.utilities/quaternion/w) | The w component. |
| [x](../../aspose.threed.utilities/quaternion/x) | The x component. |
| [y](../../aspose.threed.utilities/quaternion/y) | The y component. |
| [z](../../aspose.threed.utilities/quaternion/z) | The z component. |

### See Also

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
