---
title: MapiNamedProperty
second_title: Aspose.Email for .NET API Reference
description: Initializes a new instance of the MapiNamedPropertyaspose.email.mapi/mapinamedproperty class.
type: docs
weight: 10
url: /net/aspose.email.mapi/mapinamedproperty/mapinamedproperty/
---
## MapiNamedProperty() {#constructor}

Initializes a new instance of the [`MapiNamedProperty`](../../mapinamedproperty) class.

```csharp
public MapiNamedProperty()
```

### See Also

* class [MapiNamedProperty](../../mapinamedproperty)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(long, string, Guid, byte[]) {#constructor_4}

Initializes a new instance of the [`MapiNamedProperty`](../../mapinamedproperty) class.

```csharp
public MapiNamedProperty(long propertyTag, string nameIdentifier, Guid propertyGuid, 
    byte[] propertyValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | Int64 | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | String | The name identifier that is used to refer to a named property. |
| propertyGuid | Guid | The property unique identifier. |
| propertyValue | Byte[] | A property value. |

### See Also

* class [MapiNamedProperty](../../mapinamedproperty)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(long, long, Guid, byte[]) {#constructor_3}

Initializes a new instance of the [`MapiNamedProperty`](../../mapinamedproperty) class.

```csharp
public MapiNamedProperty(long propertyTag, long nameIdentifier, Guid propertyGuid, 
    byte[] propertyValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | Int64 | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | Int64 | The name identifier that is used to refer to a named property. |
| propertyGuid | Guid | The property unique identifier. |
| propertyValue | Byte[] | A property value. |

### See Also

* class [MapiNamedProperty](../../mapinamedproperty)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) {#constructor_1}

Initializes a new instance of the [`MapiNamedProperty`](../../mapinamedproperty) class.

```csharp
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, 
    object data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | INamedPropertyTagProvider | Property storage that can provide tag for named property |
| pd | PidLidPropertyDescriptor | Property descriptor |
| data | Object | A property value. |

### See Also

* interface [INamedPropertyTagProvider](../../inamedpropertytagprovider)
* class [PidLidPropertyDescriptor](../../pidlidpropertydescriptor)
* class [MapiNamedProperty](../../mapinamedproperty)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty)
* assembly [Aspose.Email](../../../)

---

## MapiNamedProperty(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) {#constructor_2}

Initializes a new instance of the [`MapiNamedProperty`](../../mapinamedproperty) class.

```csharp
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, 
    object data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | INamedPropertyTagProvider | Property storage that can provide tag for named property |
| pd | PidNamePropertyDescriptor | Property descriptor |
| data | Object | A property value. |

### See Also

* interface [INamedPropertyTagProvider](../../inamedpropertytagprovider)
* class [PidNamePropertyDescriptor](../../pidnamepropertydescriptor)
* class [MapiNamedProperty](../../mapinamedproperty)
* namespace [Aspose.Email.Mapi](../../mapinamedproperty)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
