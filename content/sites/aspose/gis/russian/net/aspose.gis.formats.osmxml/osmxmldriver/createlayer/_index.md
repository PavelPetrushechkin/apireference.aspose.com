---
title: CreateLayer
second_title: Справочник по Aspose.GIS for .NET API
description: Создает слой и открывает его для добавления новых объектов.
type: docs
weight: 40
url: /ru/net/aspose.gis.formats.osmxml/osmxmldriver/createlayer/
---
## CreateLayer(string, OsmXmlOptions) {#createlayer_7}

Создает слой и открывает его для добавления новых объектов.

```csharp
public VectorLayer CreateLayer(string path, OsmXmlOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к файлу. |
| options | OsmXmlOptions | Параметры, зависящие от драйвера. |

### Возвращаемое значение

Экземпляр[`VectorLayer`](../../../aspose.gis/vectorlayer).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Слой уже существует. |

### Смотрите также

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [OsmXmlOptions](../../osmxmloptions)
* class [OsmXmlDriver](../../osmxmldriver)
* пространство имен [Aspose.Gis.Formats.OsmXml](../../osmxmldriver)
* сборка [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

Создает слой и открывает его для добавления новых объектов.

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | AbstractPath | Путь к файлу. |
| options | DriverOptions | Параметры, зависящие от драйвера. |
| spatialReferenceSystem | SpatialReferenceSystem | Пространственная система отсчета. |

### Возвращаемое значение

Экземпляр[`VectorLayer`](../../../aspose.gis/vectorlayer).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Слой уже существует. |

### Смотрите также

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [DriverOptions](../../../aspose.gis/driveroptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [OsmXmlDriver](../../osmxmldriver)
* пространство имен [Aspose.Gis.Formats.OsmXml](../../osmxmldriver)
* сборка [Aspose.GIS](../../../)

---

## CreateLayer(string, OsmXmlOptions, SpatialReferenceSystem) {#createlayer_8}

Создает слой и открывает его для добавления новых объектов.

```csharp
public VectorLayer CreateLayer(string path, OsmXmlOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь к файлу. |
| options | OsmXmlOptions | Параметры, зависящие от драйвера. |
| spatialReferenceSystem | SpatialReferenceSystem | Пространственная система отсчета. |

### Возвращаемое значение

Экземпляр[`VectorLayer`](../../../aspose.gis/vectorlayer).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Слой уже существует. |
| NotSupportedException | Пространственная система отсчета не поддерживается драйвером. |

### Смотрите также

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [OsmXmlOptions](../../osmxmloptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [OsmXmlDriver](../../osmxmldriver)
* пространство имен [Aspose.Gis.Formats.OsmXml](../../osmxmldriver)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
