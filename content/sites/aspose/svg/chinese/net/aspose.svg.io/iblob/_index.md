---
title: IBlob
second_title: Aspose.SVG for .NET API 参考
description: Blob对象指的是一个字节序列有一个size属性是字节序列中的总字节数还有一个type属性是一个ASCII编码的小写字符串表示字节序列的媒体类型.
type: docs
weight: 1920
url: /zh/net/aspose.svg.io/iblob/
---
## IBlob interface

Blob对象指的是一个字节序列，有一个size属性是字节序列中的总字节数，还有一个type属性是一个ASCII编码的小写字符串，表示字节序列的媒体类型.

```csharp
public interface IBlob
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size) { get; } | 以字节数返回字节序列的大小。 在获取时，符合要求的用户代理必须返回 FileReader 或 FileReaderSync 对象可以读取的总字节数，如果 Blob 没有要读取的字节，则返回 0 . |
| [Type](../../aspose.svg.io/iblob/type) { get; } | 小写的 ASCII 编码字符串，表示 Blob 的媒体类型。 获取时，用户代理必须将 Blob 的类型作为小写的 ASCII 编码字符串返回， 以便在将其转换为字节时序列，它是一个可解析的 MIME 类型， 或空字符串 - 0 字节 - 如果类型无法确定。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice)(ulong, ulong, string) | 返回一个新的 Blob 对象，其字节范围从可选的 start 参数到但不包括可选的 end 参数 ，并且其类型属性是可选 contentType 参数的值。 |

### 也可以看看

* 命名空间 [Aspose.Svg.IO](../../aspose.svg.io)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
