---
title: SchemaLocation
second_title: Aspose.GIS for .NET API Referansı
description: URI çiftlerinin boşlukla ayrılmış listesi. Her çiftteki ilk URI ad alanının URIsidir ikinci URI ad alanının XML şemasına giden yoldur. null GmlDriveraspose.gis.formats.gml/gmldriver belgenin kök öğesinden schemaLocation okumayı deneyecek. Varsayılannull .
type: docs
weight: 50
url: /tr/net/aspose.gis.formats.gml/gmloptions/schemalocation/
---
## GmlOptions.SchemaLocation property

URI çiftlerinin boşlukla ayrılmış listesi. Her çiftteki ilk URI, ad alanının URI'sidir, ikinci URI, ad alanının XML şemasına giden yoldur. `null` ,[`GmlDriver`](../../gmldriver) belgenin kök öğesinden schemaLocation okumayı deneyecek. Varsayılan`null` .

```csharp
public string SchemaLocation { get; set; }
```

### Notlar

Aspose.GIS, oluşturmak için GML dosyasının XML şemasını kullanır.[`FeatureAttributeCollection`](../../../aspose.gis/featureattributecollection) . Varsayılan olarak, şema konumu, schemaLocation özniteliğinden çıkarılır. Böyle bir öznitelik yoksa veya geçersiz konuma işaret ediyorsa, Aspose.GIS GML dosyasını okuyamaz. Bu durumda - bu seçeneği ayarlayın, böylece Aspose.GIS schema. yükleyebilir.

### Örnekler

"http://site.com/namespace http://site.com/schema.xsd"

### Ayrıca bakınız

* class [GmlOptions](../../gmloptions)
* ad alanı [Aspose.Gis.Formats.Gml](../../gmloptions)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
