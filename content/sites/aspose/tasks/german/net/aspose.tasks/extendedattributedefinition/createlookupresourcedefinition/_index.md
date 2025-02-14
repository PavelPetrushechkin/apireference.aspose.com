---
title: CreateLookupResourceDefinition
second_title: Aspose.Tasks für .NET-API-Referenz
description: Factory-Methode die eine erweiterte Attributdefinition mit Lookup erstellt. Es hatCalculationTypeaspose.tasks/extendedattributedefinition/calculationtype ist gleichLookup und kann nur in Ressourcen verwendet werden. Sie müssen angebenfieldId undalias beim Aufruf dieser Methode. Der Feldtyp wird aus der Feld-ID abgeleitet.
type: docs
weight: 10
url: /de/net/aspose.tasks/extendedattributedefinition/createlookupresourcedefinition/
---
## CreateLookupResourceDefinition(ExtendedAttributeResource, string) {#createlookupresourcedefinition_1}

Factory-Methode, die eine erweiterte Attributdefinition mit Lookup erstellt. Es hat[`CalculationType`](../calculationtype) ist gleichLookup und kann nur in Ressourcen verwendet werden. Sie müssen angeben*fieldId* und*alias* beim Aufruf dieser Methode. Der Feldtyp wird aus der Feld-ID abgeleitet.

```csharp
public static ExtendedAttributeDefinition CreateLookupResourceDefinition(
    ExtendedAttributeResource fieldId, string alias)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldId | ExtendedAttributeResource | Die angegebene[`ExtendedAttributeResource`](../../extendedattributeresource) Feld-ID. |
| alias | String | Die angegebeneString alias. |

### Rückgabewert

Erstellte Instanz der[`ExtendedAttributeDefinition`](../../extendedattributedefinition) Klasse mit angegeben*fieldId* und*alias*.

### Beispiele

Verwenden Sie dieses Beispiel, um eine benutzerdefinierte Felddefinition für eine Ressource mit Lookup zu erstellen und sie dann mit Textwerten zu füllen:

```csharp
var resourceTextAttr = ExtendedAttributeDefinition.CreateLookupResourceDefinition(ExtendedAttributeResource.Text27, "My custom field");
resourceTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
resourceTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(resourceTextAttr);
```

### Siehe auch

* enum [ExtendedAttributeResource](../../extendedattributeresource)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* namensraum [Aspose.Tasks](../../extendedattributedefinition)
* Montage [Aspose.Tasks](../../../)

---

## CreateLookupResourceDefinition(CustomFieldType, ExtendedAttributeResource, string) {#createlookupresourcedefinition}

Factory-Methode, die eine erweiterte Attributdefinition mit Lookup erstellt. Es hat[`CalculationType`](../calculationtype) ist gleichLookup und kann nur in Ressourcen verwendet werden. Sie müssen angeben*customFieldType* ,*fieldId* und*alias* beim Aufruf dieser Methode.

```csharp
public static ExtendedAttributeDefinition CreateLookupResourceDefinition(
    CustomFieldType customFieldType, ExtendedAttributeResource fieldId, string alias)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| customFieldType | CustomFieldType | Die angegebene[`CustomFieldType`](../../customfieldtype) Typ. |
| fieldId | ExtendedAttributeResource | Die angegebene[`ExtendedAttributeResource`](../../extendedattributeresource) Feld-ID. |
| alias | String | Die angegebeneString alias. |

### Rückgabewert

Erstellte Instanz der[`ExtendedAttributeDefinition`](../../extendedattributedefinition) Klasse mit angegeben*customFieldType* ,*fieldId* und*alias*.

### Beispiele

Verwenden Sie dieses Beispiel, um eine benutzerdefinierte Felddefinition für eine Ressource mit Lookup zu erstellen und sie dann mit Textwerten zu füllen:

```csharp
var resourceTextAttr = ExtendedAttributeDefinition.CreateLookupResourceDefinition(CustomFieldType.Text, ExtendedAttributeResource.Text27, "My custom field");
resourceTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
resourceTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(resourceTextAttr);
```

### Siehe auch

* enum [CustomFieldType](../../customfieldtype)
* enum [ExtendedAttributeResource](../../extendedattributeresource)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* namensraum [Aspose.Tasks](../../extendedattributedefinition)
* Montage [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
