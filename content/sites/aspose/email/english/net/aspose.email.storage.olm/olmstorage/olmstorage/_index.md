---
title: OlmStorage
second_title: Aspose.Email for .NET API Reference
description: Initializes a new instance of the OlmStorageaspose.email.storage.olm/olmstorage class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal.
type: docs
weight: 10
url: /net/aspose.email.storage.olm/olmstorage/olmstorage/
---
## OlmStorage(TraversalExceptionsCallback) {#constructor}

Initializes a new instance of the [`OlmStorage`](../../olmstorage) class. Allows setting a callback method for handling exceptions that occur during OLM storage traversal.

```csharp
public OlmStorage(TraversalExceptionsCallback callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | TraversalExceptionsCallback | The exception callback. |

### See Also

* delegate [TraversalExceptionsCallback](../../../aspose.email.exceptions/traversalexceptionscallback)
* class [OlmStorage](../../olmstorage)
* namespace [Aspose.Email.Storage.Olm](../../olmstorage)
* assembly [Aspose.Email](../../../)

---

## OlmStorage(string) {#constructor_2}

Initializes a new instance of the [`OlmStorage`](../../olmstorage) class.

```csharp
public OlmStorage(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | OLM file name. |

### Return Value

Returns an OlmStorage instance which is loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if file name is null or empty |

### See Also

* class [OlmStorage](../../olmstorage)
* namespace [Aspose.Email.Storage.Olm](../../olmstorage)
* assembly [Aspose.Email](../../../)

---

## OlmStorage(Stream) {#constructor_1}

Initializes a new instance of the [`OlmStorage`](../../olmstorage) class.

```csharp
public OlmStorage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source stream Stream with OLM storage data. |

### Return Value

Returns an OlmStorage instance which is loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if stream is null |

### See Also

* class [OlmStorage](../../olmstorage)
* namespace [Aspose.Email.Storage.Olm](../../olmstorage)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
