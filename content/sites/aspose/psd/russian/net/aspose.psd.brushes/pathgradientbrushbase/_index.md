---
title: PathGradientBrushBase
second_title: Справочник по Aspose.PSD для .NET API
description: ПредставляетBrush../aspose.psd/brush с функцией градиента базового пути.
type: docs
weight: 180
url: /ru/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Представляет[`Brush`](../../aspose.psd/brush) с функцией градиента базового пути.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Получает или задает центральную точку градиента пути. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales) { get; set; } | Получает или задает точку фокусировки для спада градиента. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath) { get; } | Получает графический путь, на котором построена эта кисть. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints) { get; } | Получает точки пути, на которых построена эта кисть. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | Получает или устанавливает копию[`Matrix`](../../aspose.psd/matrix) который определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | Получает или задает[`WrapMode`](../../aspose.psd/wrapmode) перечисление, указывающее режим переноса для этого[`TransformBrush`](../transformbrush) . |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.psd/brush) . |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.psd/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.psd/matrix) путем добавления указанного[`Matrix`](../../aspose.psd/matrix) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.psd/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.psd/matrix) в указанном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | Сбрасывает[`Transform`](../transformbrush/transform) свойство к личности. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примечания

Обратите внимание, что при создании[`PathGradientBrushBase`](../pathgradientbrushbase) class он должен быть инициализирован как минимум двумя точками. Внутренний путь created всегда будет замкнутой фигурой, последняя точка соединяет первую точку. Эта форма заполнена этим[`PathGradientBrushBase`](../pathgradientbrushbase). Реализация GDI+ вызываетOutOfMemoryException при передаче пустых массивов или наборов точек с одинаковыми координатами. [`PathGradientBrushBase`](../pathgradientbrushbase) выдает исключение, когда массив точек содержит менее 2 точек,ArgumentException is брошен, а неOutOfMemoryException когда массив точек недопустим. Центральная точка рассчитывается как центр масс для переданных точек по умолчанию. Пользователь может изменить эту точку позже. По умолчанию шкала фокуса представляет собой пустую точку (0,0, 0,0).

### Смотрите также

* class [TransformBrush](../transformbrush)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
