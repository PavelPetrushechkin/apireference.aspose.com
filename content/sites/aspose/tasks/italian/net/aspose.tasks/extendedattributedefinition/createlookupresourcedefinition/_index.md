---
title: CreateLookupResourceDefinition
second_title: Riferimento all'API di Aspose.Tasks per .NET
description: Metodo di fabbrica che crea una definizione di attributo estesa con lookup. HaCalculationTypeaspose.tasks/extendedattributedefinition/calculationtype è uguale aLookup e può essere utilizzato solo in Risorse. È necessario specificarefieldId ealias quando si chiama questo metodo. Il tipo di campo viene dedotto da ID campo.
type: docs
weight: 10
url: /it/net/aspose.tasks/extendedattributedefinition/createlookupresourcedefinition/
---
## CreateLookupResourceDefinition(ExtendedAttributeResource, string) {#createlookupresourcedefinition_1}

Metodo di fabbrica che crea una definizione di attributo estesa con lookup. Ha[`CalculationType`](../calculationtype) è uguale aLookup e può essere utilizzato solo in Risorse. È necessario specificare*fieldId* e*alias* quando si chiama questo metodo. Il tipo di campo viene dedotto da ID campo.

```csharp
public static ExtendedAttributeDefinition CreateLookupResourceDefinition(
    ExtendedAttributeResource fieldId, string alias)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldId | ExtendedAttributeResource | Il specificato[`ExtendedAttributeResource`](../../extendedattributeresource) ID campo. |
| alias | String | Il specificatoString alias. |

### Valore di ritorno

Istanza creata di[`ExtendedAttributeDefinition`](../../extendedattributedefinition) classe con specificato*fieldId* e*alias*.

### Esempi

Utilizzare questo esempio per creare una definizione di campo personalizzata per una risorsa con ricerca e quindi riempirla con valori di testo:

```csharp
var resourceTextAttr = ExtendedAttributeDefinition.CreateLookupResourceDefinition(ExtendedAttributeResource.Text27, "My custom field");
resourceTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
resourceTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(resourceTextAttr);
```

### Guarda anche

* enum [ExtendedAttributeResource](../../extendedattributeresource)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* spazio dei nomi [Aspose.Tasks](../../extendedattributedefinition)
* assemblea [Aspose.Tasks](../../../)

---

## CreateLookupResourceDefinition(CustomFieldType, ExtendedAttributeResource, string) {#createlookupresourcedefinition}

Metodo di fabbrica che crea una definizione di attributo estesa con lookup. Ha[`CalculationType`](../calculationtype) è uguale aLookup e può essere utilizzato solo in Risorse. È necessario specificare*customFieldType* ,*fieldId* e*alias* quando chiama questo metodo.

```csharp
public static ExtendedAttributeDefinition CreateLookupResourceDefinition(
    CustomFieldType customFieldType, ExtendedAttributeResource fieldId, string alias)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| customFieldType | CustomFieldType | Il specificato[`CustomFieldType`](../../customfieldtype) genere. |
| fieldId | ExtendedAttributeResource | Il specificato[`ExtendedAttributeResource`](../../extendedattributeresource) ID campo. |
| alias | String | Il specificatoString alias. |

### Valore di ritorno

Istanza creata di[`ExtendedAttributeDefinition`](../../extendedattributedefinition) classe con specificato*customFieldType* ,*fieldId* e*alias*.

### Esempi

Utilizzare questo esempio per creare una definizione di campo personalizzata per una risorsa con ricerca e quindi riempirla con valori di testo:

```csharp
var resourceTextAttr = ExtendedAttributeDefinition.CreateLookupResourceDefinition(CustomFieldType.Text, ExtendedAttributeResource.Text27, "My custom field");
resourceTextAttr.AddLookupValue(new Value { Id = 1, Val = "Text value 1", Description = "Text value description 1" });
resourceTextAttr.AddLookupValue(new Value { Id = 2, Val = "Text value 2", Description = "Text value description 2" });
project.ExtendedAttributes.Add(resourceTextAttr);
```

### Guarda anche

* enum [CustomFieldType](../../customfieldtype)
* enum [ExtendedAttributeResource](../../extendedattributeresource)
* class [ExtendedAttributeDefinition](../../extendedattributedefinition)
* spazio dei nomi [Aspose.Tasks](../../extendedattributedefinition)
* assemblea [Aspose.Tasks](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Tasks.dll -->
