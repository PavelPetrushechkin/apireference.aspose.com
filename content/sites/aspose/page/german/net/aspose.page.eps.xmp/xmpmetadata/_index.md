---
title: XmpMetadata
second_title: Aspose.Page für .NET-API-Referenz
description: Bietet Zugriff auf den XMPMetadatenstrom.
type: docs
weight: 130
url: /de/net/aspose.page.eps.xmp/xmpmetadata/
---
## XmpMetadata class

Bietet Zugriff auf den XMP-Metadatenstrom.

```csharp
public sealed class XmpMetadata : IDictionary<string, XmpValue>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.page.eps.xmp/xmpmetadata/count) { get; } | Ruft die Anzahl der Elemente in der Sammlung ab. |
| [IsFixedSize](../../aspose.page.eps.xmp/xmpmetadata/isfixedsize) { get; } | Überprüft, ob die Sammlung eine feste Größe hat. |
| [IsReadOnly](../../aspose.page.eps.xmp/xmpmetadata/isreadonly) { get; } | Überprüft, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.page.eps.xmp/xmpmetadata/issynchronized) { get; } | Überprüft, ob die Sammlung synchronisiert ist. |
| [Item](../../aspose.page.eps.xmp/xmpmetadata/item) { get; set; } | Ruft Daten aus Metadaten ab oder legt sie fest. |
| [Keys](../../aspose.page.eps.xmp/xmpmetadata/keys) { get; } | Ruft Sammlung von Metadatenschlüsseln ab. |
| [NamespaceManager](../../aspose.page.eps.xmp/xmpmetadata/namespacemanager) { get; } | Ruft Namespace-Manager ab. |
| [SyncRoot](../../aspose.page.eps.xmp/xmpmetadata/syncroot) { get; } | Ruft das Sammlungssynchronisierungsobjekt ab. |
| [Values](../../aspose.page.eps.xmp/xmpmetadata/values) { get; } | Ruft Werte in den Metadaten ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add)(KeyValuePair&lt;string, XmpValue&gt;) | Fügt ein Paar mit Schlüssel und Wert in das Wörterbuch ein. |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add_2)(string, object) | Fügt Metadaten Wert hinzu. |
| [Add](../../aspose.page.eps.xmp/xmpmetadata/add#add_1)(string, XmpValue) | Fügt Metadaten Wert hinzu. |
| [AddArrayItem](../../aspose.page.eps.xmp/xmpmetadata/addarrayitem#addarrayitem)(string, XmpValue) | Fügt einen Wert in ein Array hinzu. Der Wert wird am Ende des Arrays hinzugefügt. |
| [AddArrayItem](../../aspose.page.eps.xmp/xmpmetadata/addarrayitem#addarrayitem_1)(string, int, XmpValue) | Fügt einen Wert in ein Array um den angegebenen Index hinzu. |
| [AddNamedValue](../../aspose.page.eps.xmp/xmpmetadata/addnamedvalue)(string, string, XmpValue) | Fügt einen benannten Wert in eine Struktur ein. |
| [Clear](../../aspose.page.eps.xmp/xmpmetadata/clear)() | Löscht Metadaten. |
| [Contains](../../aspose.page.eps.xmp/xmpmetadata/contains#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Prüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [Contains](../../aspose.page.eps.xmp/xmpmetadata/contains#contains_1)(string) | Überprüft, ob der Schlüssel in den Metadaten enthalten ist. |
| [ContainsKey](../../aspose.page.eps.xmp/xmpmetadata/containskey)(string) | Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.page.eps.xmp/xmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) | Kopiert Elemente der Sammlung in ein Array. |
| [GetEnumerator](../../aspose.page.eps.xmp/xmpmetadata/getenumerator)() | Gibt den Wörterbuch-Enumerator zurück. |
| [GetNamespaceUriByPrefix](../../aspose.page.eps.xmp/xmpmetadata/getnamespaceuribyprefix)(string) | Gibt Namespace-URI nach Präfix zurück. |
| [GetPrefixByNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/getprefixbynamespaceuri)(string) | Gibt Präfix nach Namespace-URI zurück. |
| [RegisterNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/registernamespaceuri#registernamespaceuri)(string, string) | Registriert Namespace-URI. |
| [RegisterNamespaceUri](../../aspose.page.eps.xmp/xmpmetadata/registernamespaceuri#registernamespaceuri_1)(string, string, string) | Registriert Namespace-URI. |
| [Remove](../../aspose.page.eps.xmp/xmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Entfernt Schlüssel/Wert-Paare aus der Sammlung. |
| [Remove](../../aspose.page.eps.xmp/xmpmetadata/remove#remove_1)(string) | Entfernt Eintrag aus Metadaten. |
| [SetArrayItem](../../aspose.page.eps.xmp/xmpmetadata/setarrayitem)(string, int, XmpValue) | Legt den Wert in einem Array fest. Der vorherige Wert wird durch den neuen ersetzt. |
| [SetNamedValue](../../aspose.page.eps.xmp/xmpmetadata/setnamedvalue)(string, string, XmpValue) | Setzt einen benannten Wert in eine Struktur. Der vorherige benannte Wert wird, falls bereits vorhanden, durch einen neuen ersetzt. |
| [TryGetValue](../../aspose.page.eps.xmp/xmpmetadata/trygetvalue)(string, out XmpValue) | Versucht, den Schlüssel im Wörterbuch zu finden, und ruft den Wert ab, falls gefunden. |

### Siehe auch

* class [XmpValue](../xmpvalue)
* namensraum [Aspose.Page.EPS.XMP](../../aspose.page.eps.xmp)
* Montage [Aspose.Page](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Page.dll -->
