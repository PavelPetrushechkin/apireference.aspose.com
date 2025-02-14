﻿---
title: PlainTextDocument constructor
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.PlainTextDocument constructor"
type: docs
weight: 10
url: /python-net/aspose.words/plaintextdocument/__init__/
---

## PlainTextDocument(file_name) {#str}

Creates a plain text document from a file. Automatically detects the file format.


```python
def __init__(self, file_name: str):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| file_name | str |  |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileFormatException](../../unsupportedfileformatexception/) | The document format is not recognized or not supported. |
| [FileCorruptedException](../../filecorruptedexception/) | The document appears to be corrupted and cannot be loaded. |
| System.Exception | There is a problem with the document and it should be reported to Aspose.Words developers. |
| System.IO.IOException | There is an input/output exception. |
| [IncorrectPasswordException](../../incorrectpasswordexception/) | The document is encrypted and requires a password to open, but you supplied an incorrect password. |
| System.ArgumentException | The name of the file cannot be null or empty string. |

## PlainTextDocument(file_name, load_options) {#str_loadoptions}

Creates a plain text document from a file. Allows to specify additional options such as an encryption password.


```python
def __init__(self, file_name: str, load_options: aspose.words.loading.LoadOptions):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| file_name | str |  |
| load_options | [LoadOptions](../../../aspose.words.loading/loadoptions/) |  |




### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileFormatException](../../unsupportedfileformatexception/) | The document format is not recognized or not supported. |
| [FileCorruptedException](../../filecorruptedexception/) | The document appears to be corrupted and cannot be loaded. |
| System.Exception | There is a problem with the document and it should be reported to Aspose.Words developers. |
| System.IO.IOException | There is an input/output exception. |
| [IncorrectPasswordException](../../incorrectpasswordexception/) | The document is encrypted and requires a password to open, but you supplied an incorrect password. |
| System.ArgumentException | The name of the file cannot be null or empty string. |

## PlainTextDocument(stream) {#bytesio}

Creates a plain text document from a stream. Automatically detects the file format.


```python
def __init__(self, stream: BytesIO):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | BytesIO |  |

The document must be stored at the beginning of the stream. The stream must support random positioning.




### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileFormatException](../../unsupportedfileformatexception/) | The document format is not recognized or not supported. |
| [FileCorruptedException](../../filecorruptedexception/) | The document appears to be corrupted and cannot be loaded. |
| System.Exception | There is a problem with the document and it should be reported to Aspose.Words developers. |
| System.IO.IOException | There is an input/output exception. |
| [IncorrectPasswordException](../../incorrectpasswordexception/) | The document is encrypted and requires a password to open, but you supplied an incorrect password. |
| System.ArgumentNullException | The stream cannot be null. |
| System.NotSupportedException | The stream does not support reading or seeking. |
| System.ObjectDisposedException | The stream is a disposed object. |

## PlainTextDocument(stream, load_options) {#bytesio_loadoptions}

Creates a plain text document from a stream. Allows to specify additional options such as an encryption password.


```python
def __init__(self, stream: BytesIO, load_options: aspose.words.loading.LoadOptions):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | BytesIO |  |
| load_options | [LoadOptions](../../../aspose.words.loading/loadoptions/) |  |

The document must be stored at the beginning of the stream. The stream must support random positioning.




### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileFormatException](../../unsupportedfileformatexception/) | The document format is not recognized or not supported. |
| [FileCorruptedException](../../filecorruptedexception/) | The document appears to be corrupted and cannot be loaded. |
| System.Exception | There is a problem with the document and it should be reported to Aspose.Words developers. |
| System.IO.IOException | There is an input/output exception. |
| [IncorrectPasswordException](../../incorrectpasswordexception/) | The document is encrypted and requires a password to open, but you supplied an incorrect password. |
| System.ArgumentNullException | The stream cannot be null. |
| System.NotSupportedException | The stream does not support reading or seeking. |
| System.ObjectDisposedException | The stream is a disposed object. |

## Examples

Shows how to load the contents of a Microsoft Word document in plaintext.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
builder.writeln("Hello world!")

doc.save(ARTIFACTS_DIR + "PlainTextDocument.load.docx")

plaintext = aw.PlainTextDocument(ARTIFACTS_DIR + "PlainTextDocument.load.docx")

self.assertEqual("Hello world!", plaintext.text.strip())
```

Shows how to load the contents of an encrypted Microsoft Word document in plaintext.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)
builder.writeln("Hello world!")

save_options = aw.saving.OoxmlSaveOptions()
save_options.password = "MyPassword"

doc.save(ARTIFACTS_DIR + "PlainTextDocument.load_encrypted.docx", save_options)

load_options = aw.loading.LoadOptions()
load_options.password = "MyPassword"

plaintext = aw.PlainTextDocument(ARTIFACTS_DIR + "PlainTextDocument.load_encrypted.docx", load_options)

self.assertEqual("Hello world!", plaintext.text.strip())
```

Shows how to load the contents of a Microsoft Word document in plaintext using stream.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.writeln("Hello world!")
doc.save(ARTIFACTS_DIR + "PlainTextDocument.load_from_stream.docx")

with open(ARTIFACTS_DIR + "PlainTextDocument.load_from_stream.docx", "rb") as stream:

    plaintext = aw.PlainTextDocument(stream)

    self.assertEqual("Hello world!", plaintext.text.strip())
```

Shows how to load the contents of an encrypted Microsoft Word document in plaintext using stream.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.writeln("Hello world!")

save_options = aw.saving.OoxmlSaveOptions()
save_options.password = "MyPassword"

doc.save(ARTIFACTS_DIR + "PlainTextDocument.load_encrypted_using_stream.docx", save_options)

load_options = aw.loading.LoadOptions()
load_options.password = "MyPassword"

with open(ARTIFACTS_DIR + "PlainTextDocument.load_encrypted_using_stream.docx", "rb") as stream:

    plaintext = aw.PlainTextDocument(stream, load_options)

    self.assertEqual("Hello world!", plaintext.text.strip())
```

## See Also

* module [aspose.words](../../)
* class [PlainTextDocument](../)

