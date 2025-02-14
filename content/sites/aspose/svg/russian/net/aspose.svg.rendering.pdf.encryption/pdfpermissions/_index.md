---
title: PdfPermissions
second_title: Справочник по Aspose.SVG для .NET API
description: Это перечисление представляет права пользователя для pdf.
type: docs
weight: 2890
url: /ru/net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Это перечисление представляет права пользователя для pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| PrintDocument | `4` | (Обработчики безопасности версии 2) Распечатайте документ. (обработчики безопасности версии 3 или выше) Распечатайте документ (возможно, не с самым высоким уровнем качества, в зависимости от того, установлено ли также PrintingQuality). |
| ModifyContent | `8` | Изменить содержимое документа с помощью операций, отличных от операций, контролируемых ModifyTextAnnotations, FillForm и 11. |
| ExtractContent | `10` | Обработчики безопасности версии 2) Копировать или иным образом извлекать текст и графику из документа, включая извлечение текста и графики (для обеспечения доступности для пользователей с ограниченными возможностями или для других целей). (Обработчики безопасности версии 3 или выше) Копировать или иным образом извлекать текст и графику из документа с помощью операций, отличных от операций, контролируемых ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Добавление или изменение текстовых аннотаций, заполнение полей интерактивной формы и, если также установлено значение ModifyContent, создание или изменение полей интерактивной формы (включая поля подписи). |
| FillForm | `100` | (обработчики безопасности версии 3 или выше) Заполните существующие поля интерактивной формы (включая поля подписи), даже если параметр ModifyTextAnnotations не установлен. |
| ExtractContentWithDisabilities | `200` | (обработчики безопасности версии 3 или выше) Извлечение текста и графики (в целях обеспечения доступности для пользователей с ограниченными возможностями или для других целей). |
| AssembleDocument | `400` | (обработчики безопасности версии 3 или выше) Соберите документ (вставьте, поверните или удалите страницы и создайте закладки или эскизы), даже если ModifyContent не установлен. |
| PrintingQuality | `800` | (обработчики безопасности версии 3 или выше) Печать документа в представление, из которого может быть создана точная цифровая копия содержимого PDF. Когда этот бит сброшен (и установлен бит 3), печать ограничена -уровень представления внешности, возможно ухудшенного качества. |

### Смотрите также

* пространство имен [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption)
* сборка [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
