---
title: IStyleSheet
second_title: Справочник по Aspose.SVG для .NET API
description: Интерфейс StyleSheet является абстрактным базовым интерфейсом для любого типа таблицы стилей. Он представляет собой единую таблицу стилей связанную со структурированным документом.
type: docs
weight: 740
url: /ru/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

Интерфейс StyleSheet является абстрактным базовым интерфейсом для любого типа таблицы стилей. Он представляет собой единую таблицу стилей, связанную со структурированным документом.

```csharp
public interface IStyleSheet
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled) { get; set; } | false, если таблица стилей применяется к документу. правда если нет. Изменение этого атрибута может привести к новому разрешению стиля для документа. Таблица стилей применяется только в том случае, если присутствует соответствующее определение среды, а атрибут disabled имеет значение false. Таким образом, если носитель не применяется к текущему пользовательскому агенту, атрибут disabled игнорируется. |
| [Href](../../aspose.svg.dom.css/istylesheet/href) { get; } | Если таблица стилей является связанной таблицей стилей, значением ее атрибута является ее местоположение. Для встроенных таблиц стилей значение этого атрибута равно null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media) { get; } | Предполагаемый целевой носитель для информации о стиле. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode) { get; } | Узел, который связывает эту таблицу стилей с документом. Для HTML это может быть соответствующий элемент LINK или STYLE. Для XML это может быть инструкция по обработке ссылок. Для таблиц стилей, которые включены в другие таблицы стилей, значение этого атрибута равно null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet) { get; } | Для языков таблиц стилей, которые поддерживают концепцию включения таблиц стилей, этот атрибут представляет включающую таблицу стилей, если она существует. Если таблица стилей является таблицей стилей верхнего уровня или язык таблицы стилей не поддерживает включение, значение этого атрибута равно null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title) { get; } | Консультативный заголовок. |
| [Type](../../aspose.svg.dom.css/istylesheet/type) { get; } | Указывает язык таблицы стилей для этой таблицы стилей. Язык таблицы стилей указывается как тип содержимого (например, "text/css"). |

### Смотрите также

* пространство имен [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
