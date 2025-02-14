---
title: TraditionalEncryptionSettings
second_title: Aspose.ZIP for .NET API Referansı
description: Yeni bir örneğini başlatırTraditionalEncryptionSettingsaspose.zip.saving/traditionalencryptionsettings sınıf.
type: docs
weight: 10
url: /tr/net/aspose.zip.saving/traditionalencryptionsettings/traditionalencryptionsettings/
---
## TraditionalEncryptionSettings(string) {#constructor_1}

Yeni bir örneğini başlatır[`TraditionalEncryptionSettings`](../../traditionalencryptionsettings) sınıf.

```csharp
public TraditionalEncryptionSettings(string password)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| password | String | Şifreleme için şifre. |

### Örnekler

```csharp
using (var archive = new Archive(new ArchiveEntrySettings(null, new TraditionalEncryptionSettings("p@s$"))))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Ayrıca bakınız

* class [TraditionalEncryptionSettings](../../traditionalencryptionsettings)
* ad alanı [Aspose.Zip.Saving](../../traditionalencryptionsettings)
* toplantı [Aspose.Zip](../../../)

---

## TraditionalEncryptionSettings(string, Encoding) {#constructor_2}

Yeni bir örneğini başlatır[`TraditionalEncryptionSettings`](../../traditionalencryptionsettings) kullanıcı tanımlı kodlamaya sahip sınıf.

```csharp
public TraditionalEncryptionSettings(string password, Encoding encoding)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| password | String | Şifreleme için şifre. |
| encoding | Encoding | Şifre karakterleri için kodlama. |

### Notlar

Bu kurucunun kullanımı önerilmez. Kodlamayı ayarlamak standartla çelişebilir ve uyumsuz arşiv oluşturabilir.

### Örnekler

```csharp
using (var archive = new Archive(new ArchiveEntrySettings(null, new TraditionalEncryptionSettings("p£s$", System.Text.Encoding.ASCII))))
{
    archive.CreateEntry("data.bin", "data.bin");
    archive.Save(zipFile);
}
```

### Ayrıca bakınız

* class [TraditionalEncryptionSettings](../../traditionalencryptionsettings)
* ad alanı [Aspose.Zip.Saving](../../traditionalencryptionsettings)
* toplantı [Aspose.Zip](../../../)

---

## TraditionalEncryptionSettings() {#constructor}

Yeni bir örneğini başlatır[`TraditionalEncryptionSettings`](../../traditionalencryptionsettings) şifresiz sınıf.

```csharp
public TraditionalEncryptionSettings()
```

### Ayrıca bakınız

* class [TraditionalEncryptionSettings](../../traditionalencryptionsettings)
* ad alanı [Aspose.Zip.Saving](../../traditionalencryptionsettings)
* toplantı [Aspose.Zip](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Zip.dll -->
