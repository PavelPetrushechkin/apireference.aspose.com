---
title: OutputStream
second_title: Aspose.SVG for .NET API 参考
description: 代理流包装真实的输出流并控制对它的访问 OutputStream./outputstream包含描述输出流位置的 URI 数据
type: docs
weight: 1980
url: /zh/net/aspose.svg.io/outputstream/
---
## OutputStream class

代理流包装真实的输出流并控制对它的访问。 [`OutputStream`](../outputstream)包含描述输出流位置的 URI 数据。

```csharp
public class OutputStream : Stream
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [OutputStream](outputstream)(Stream, string) | 初始化[`OutputStream`](../outputstream)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [CanRead](../../aspose.svg.io/outputstream/canread) { get; } | 获取一个值，该值指示包装的输出流是否支持读取。 |
| override [CanSeek](../../aspose.svg.io/outputstream/canseek) { get; } | 获取一个值，该值指示包装的输出流是否支持搜索。 |
| override [CanWrite](../../aspose.svg.io/outputstream/canwrite) { get; } | 获取一个值，该值指示包装的输出流是否支持写入。 |
| override [Length](../../aspose.svg.io/outputstream/length) { get; } | 获取包装输出流的字节长度。 |
| override [Position](../../aspose.svg.io/outputstream/position) { get; set; } | 获取或设置包装输出流中的位置。 |
| [Uri](../../aspose.svg.io/outputstream/uri) { get; } | 获取流位置的 URI。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Close](../../aspose.svg.io/outputstream/close)() | 关闭包装的输出流和当前流。 |
| override [Flush](../../aspose.svg.io/outputstream/flush)() | 清除包装输出流的所有缓冲区，并导致任何缓冲数据写入底层设备。 |
| override [Read](../../aspose.svg.io/outputstream/read)(byte[], int, int) | 从包装的输出流 中读取字节序列，并将流中的位置前进读取的字节数。 |
| override [Seek](../../aspose.svg.io/outputstream/seek)(long, SeekOrigin) | 设置包装输出流中的位置。 |
| override [SetLength](../../aspose.svg.io/outputstream/setlength)(long) | 设置包装输出流的长度。 |
| override [Write](../../aspose.svg.io/outputstream/write)(byte[], int, int) | 将字节序列写入包装的 output 流，并将此流中的当前位置前进写入的 字节数。 |

### 也可以看看

* 命名空间 [Aspose.Svg.IO](../../aspose.svg.io)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
