---
title: SetValue
second_title: Aspose.GIS for .NET API 参考
description: 设置属性的新值
type: docs
weight: 100
url: /zh/net/aspose.gis/feature/setvalue/
---
## Feature.SetValue&lt;T&gt; method

设置属性的新值。

```csharp
public void SetValue<T>(string attributeName, T value)
```

| 范围 | 描述 |
| --- | --- |
| T | 值的类型。 |
| attributeName | 属性的名称。 |
| value | 属性的值。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 属性名称是`null`. |
| ArgumentException | 此层中不存在具有此名称的属性。 |
| InvalidOperationException | 该属性未锁定。 |
| InvalidCastException | 值的类型未实现IConvertible. |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 由于溢出，转换失败。 |

### 评论

此方法自动将值转换为属性的类型。

### 也可以看看

* class [Feature](../../feature)
* 命名空间 [Aspose.Gis](../../feature)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
