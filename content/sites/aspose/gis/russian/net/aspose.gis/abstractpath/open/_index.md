---
title: Open
second_title: Справочник по Aspose.GIS for .NET API
description: Открывает этоАннотацияПутьв виде файла.
type: docs
weight: 120
url: /ru/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

Открывает это`АннотацияПуть`в виде файла.

```csharp
public abstract Stream Open(FileAccess access)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| access | FileAccess | Определяет подмножество операций, которые могут быть выполнены наStream. |

### Возвращаемое значение

АStream открывается с указаннымFileAccess .

### Примечания

Если*access* имеет флагWrite установлен, а файл не существует, его должен создать наследник. Ан`АннотацияПуть` можно открывать несколько раз`Aspose.ГИС` . Это необходимо для независимого чтения файла file несколькими потоками. Вы не должны кэшировать результат, а скорее возвращать новыйStream каждый раз вызывается этот метод.

### Смотрите также

* class [AbstractPath](../../abstractpath)
* пространство имен [Aspose.Gis](../../abstractpath)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
