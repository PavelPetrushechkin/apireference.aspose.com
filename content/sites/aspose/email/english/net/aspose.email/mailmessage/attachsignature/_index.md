---
title: AttachSignature
second_title: Aspose.Email for .NET API Reference
description: Creates a signed message. Creates a readonly copy of the specified MailMessage and adds a digital signature to it.
type: docs
weight: 400
url: /net/aspose.email/mailmessage/attachsignature/
---
## AttachSignature(X509Certificate2, bool) {#attachsignature_3}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | X.509 certificate. |
| detached | Boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

### See Also

* class [MailMessage](../../mailmessage)
* namespace [Aspose.Email](../../mailmessage)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner, bool) {#attachsignature_1}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | System.Security.Cryptography.Pkcs.CmsSigner. |
| detached | Boolean | .If detached is true, the signature is detached.If detached is false(the default), the signature is not detached. |

### Return Value

The signed MailMessage.

### See Also

* class [MailMessage](../../mailmessage)
* namespace [Aspose.Email](../../mailmessage)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(X509Certificate2) {#attachsignature_2}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | X.509 certificate. |

### Return Value

The signed MailMessage.

### See Also

* class [MailMessage](../../mailmessage)
* namespace [Aspose.Email](../../mailmessage)
* assembly [Aspose.Email](../../../)

---

## AttachSignature(CmsSigner) {#attachsignature}

Creates a signed message. Creates a read-only copy of the specified MailMessage and adds a digital signature to it.

```csharp
public virtual MailMessage AttachSignature(CmsSigner signer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signer | CmsSigner | System.Security.Cryptography.Pkcs.CmsSigner. |

### Return Value

The signed MailMessage.

### See Also

* class [MailMessage](../../mailmessage)
* namespace [Aspose.Email](../../mailmessage)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
