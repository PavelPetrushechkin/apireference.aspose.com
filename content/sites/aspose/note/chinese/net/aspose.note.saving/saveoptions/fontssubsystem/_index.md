---
title: FontsSubsystem
second_title: Aspose.Note for .NET API 参考
description: 获取或设置保存时要使用的字体设置
type: docs
weight: 10
url: /zh/net/aspose.note.saving/saveoptions/fontssubsystem/
---
## SaveOptions.FontsSubsystem property

获取或设置保存时要使用的字体设置

```csharp
public FontsSubsystem FontsSubsystem { get; set; }
```

### 例子

展示如何使用指定的默认字体以 pdf 格式保存文档。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// 将文档加载到 Aspose.Note。
Document oneFile = new Document(Path.Combine(dataDir, "missing-font.one"));

// 将文档保存为 PDF
dataDir = dataDir + "SaveUsingDocumentFontsSubsystemWithDefaultFontName_out.pdf";
oneFile.Save(dataDir, new PdfSaveOptions() 
                      {
                          FontsSubsystem = DocumentFontsSubsystem.UsingDefaultFont("Times New Roman")
                      });
```

演示如何使用文件中的默认字体将文档保存为 pdf 格式。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

string fontFile = Path.Combine(dataDir, "geo_1.ttf");

// 将文档加载到 Aspose.Note。
Document oneFile = new Document(Path.Combine(dataDir, "missing-font.one"));

// 将文档保存为 PDF
dataDir = dataDir + "SaveUsingDocumentFontsSubsystemWithDefaultFontFromFile_out.pdf";
oneFile.Save(dataDir, new PdfSaveOptions()
                          {
                              FontsSubsystem = DocumentFontsSubsystem.UsingDefaultFontFromFile(fontFile)
                          });
```

演示如何使用流中的默认字体以 pdf 格式保存文档。

```csharp
// 文档目录的路径。
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

string fontFile = Path.Combine(dataDir, "geo_1.ttf");

// 将文档加载到 Aspose.Note。
Document oneFile = new Document(Path.Combine(dataDir, "missing-font.one"));

// 将文档保存为 PDF
dataDir = dataDir + "SaveUsingDocumentFontsSubsystemWithDefaultFontFromStream_out.pdf";

using (var stream = File.Open(fontFile, FileMode.Open, FileAccess.Read, FileShare.Read))
{
    oneFile.Save(dataDir, new PdfSaveOptions()
                              {
                                  FontsSubsystem = DocumentFontsSubsystem.UsingDefaultFontFromStream(stream)
                              });
}
```

### 也可以看看

* class [FontsSubsystem](../../../aspose.note.fonts/fontssubsystem)
* class [SaveOptions](../../saveoptions)
* 命名空间 [Aspose.Note.Saving](../../saveoptions)
* 部件 [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
