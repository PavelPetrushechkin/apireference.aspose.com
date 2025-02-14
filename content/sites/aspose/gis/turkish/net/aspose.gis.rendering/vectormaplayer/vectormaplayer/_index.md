---
title: VectorMapLayer
second_title: Aspose.GIS for .NET API Referansı
description: Varsayılan sembolleştirici ile yeni örnek oluşturur.
type: docs
weight: 10
url: /tr/net/aspose.gis.rendering/vectormaplayer/vectormaplayer/
---
## VectorMapLayer(FeaturesSequence) {#constructor}

Varsayılan sembolleştirici ile yeni örnek oluşturur.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | Özellikler dizisi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |

### Ayrıca bakınız

* class [FeaturesSequence](../../../aspose.gis/featuressequence)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer) {#constructor_1}

Varsayılan sembolleştirici ile yeni örnek oluşturur.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | Özellikler dizisi. |
| symbolizer | VectorSymbolizer | Katmanı oluşturmak için kullanılacak sembolleştirici. Eğer`null`, varsayılan simgeleyici kullanılacaktır. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |

### Ayrıca bakınız

* class [FeaturesSequence](../../../aspose.gis/featuressequence)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer, Labeling) {#constructor_2}

Varsayılan sembolleştirici ile yeni örnek oluşturur.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer, 
    Labeling labeling)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | Özellikler dizisi. |
| symbolizer | VectorSymbolizer | Katmanı oluşturmak için kullanılacak sembolleştirici. Eğer`null`, varsayılan simgeleyici kullanılacaktır. |
| labeling | Labeling | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer`null` , varsayılan[`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling) kullanılacak. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |

### Ayrıca bakınız

* class [FeaturesSequence](../../../aspose.gis/featuressequence)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, bool) {#constructor_5}

Varsayılan sembolleştirici ile yeni örnek oluşturur.

```csharp
public VectorMapLayer(VectorLayer layer, bool keepOpen = true)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layer | VectorLayer | Vektör katmanı. |
| keepOpen | Boolean | `true` sonra katmanı açık bırakmak için[`VectorMapLayer`](../../vectormaplayer) nesne atılır; aksi halde,`false` . |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Katman (şimdiki değeri)`null`. |

### Ayrıca bakınız

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, bool) {#constructor_4}

Yeni örnek oluşturur.

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, bool keepOpen = true)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layer | VectorLayer | Vektör katmanı. |
| symbolizer | VectorSymbolizer | Katmanı oluşturmak için kullanılacak sembolleştirici. Eğer`null`, varsayılan simgeleyici kullanılacaktır. |
| keepOpen | Boolean | `true` sonra katmanı açık bırakmak için[`VectorMapLayer`](../../vectormaplayer) nesne atılır; aksi halde,`false` . |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Katman (şimdiki değeri)`null`. |

### Ayrıca bakınız

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, Labeling, bool) {#constructor_3}

Yeni örnek oluşturur.

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    bool keepOpen = true)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layer | VectorLayer | Vektör katmanı. |
| symbolizer | VectorSymbolizer | Katmanı oluşturmak için kullanılacak Sembolleştirici. Eğer`null` varsayılan simgeleyici kullanılacaktır. |
| labeling | Labeling | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer`null` , varsayılan[`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling) kullanılacak. |
| keepOpen | Boolean | `true` sonra katmanı açık bırakmak için[`VectorMapLayer`](../../vectormaplayer) nesne atılır; aksi halde,`false` . |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Katman (şimdiki değeri)`null`. |

### Ayrıca bakınız

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling)
* class [VectorMapLayer](../../vectormaplayer)
* ad alanı [Aspose.Gis.Rendering](../../vectormaplayer)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
