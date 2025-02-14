---
title: FontSavingCallback
second_title: Aspose.Note for .NET API Reference
description: Gets or sets the callback that is called to create resource to store font.
type: docs
weight: 90
url: /net/aspose.note.saving/htmlsaveoptions/fontsavingcallback/
---
## HtmlSaveOptions.FontSavingCallback property

Gets or sets the callback that is called to create resource to store font.

```csharp
public IFontSavingCallback FontSavingCallback { get; set; }
```

### Examples

Shows how to save a document in html format with storing all resources(css/fonts/images) by using user-defined callbacks.

```csharp
// The code below creates 'documentFolder' folder containing document.html, 'css' folder with 'style.css' file, 'images' folder with images and 'fonts' folder with fonts.
// 'style.css' file will contain at the end the following string "/* This line is appended to stream manually by user */"
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

### See Also

* interface [IFontSavingCallback](../../../aspose.note.saving.html/ifontsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [Aspose.Note.Saving](../../htmlsaveoptions)
* assembly [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
