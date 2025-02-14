---
title: FontSavingCallback
second_title: Aspose.Note for .NET API 参考
description: 获取或设置为创建资源存储字体而调用的回调
type: docs
weight: 90
url: /zh/net/aspose.note.saving/htmlsaveoptions/fontsavingcallback/
---
## HtmlSaveOptions.FontSavingCallback property

获取或设置为创建资源存储字体而调用的回调。

```csharp
public IFontSavingCallback FontSavingCallback { get; set; }
```

### 例子

展示如何使用用户定义的回调将文档保存为 html 格式并存储所有资源（css/fonts/images）。

```csharp
// 下面的代码创建包含 document.html 的“documentFolder”文件夹，包含“style.css”文件的“css”文件夹，包含图像的“images”文件夹和包含字体的“fonts”文件夹。
// 'style.css' 文件将在末尾包含以下字符串“/* 此行由用户手动附加到流 */”
var savingCallbacks = new UserSavingCallbacks()
                          {
                              RootFolder = "documentFolder",
                              CssFolder = "css",
                              KeepCssStreamOpened = true,
                              ImagesFolder = "images",
                              FontsFolder = "fonts"
                          };
var options = new HtmlSaveOptions
              {
                  FontFaceTypes = FontFaceType.Ttf,
                  CssSavingCallback = savingCallbacks,
                  FontSavingCallback = savingCallbacks,
                  ImageSavingCallback = savingCallbacks
              };

if (!Directory.Exists(savingCallbacks.RootFolder))
{
    Directory.CreateDirectory(savingCallbacks.RootFolder);
}

string dataDir = RunExamples.GetDataDir_LoadingAndSaving();
var document = new Document(Path.Combine(dataDir, "Aspose.one"));

using (var stream = File.Create(Path.Combine(savingCallbacks.RootFolder, "document.html")))
{
    document.Save(stream, options);
}

using (var writer = new StreamWriter(savingCallbacks.CssStream))
{
    writer.WriteLine();
    writer.WriteLine("/* This line is appended to stream manually by user */");
}
```

### 也可以看看

* interface [IFontSavingCallback](../../../aspose.note.saving.html/ifontsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* 命名空间 [Aspose.Note.Saving](../../htmlsaveoptions)
* 部件 [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
