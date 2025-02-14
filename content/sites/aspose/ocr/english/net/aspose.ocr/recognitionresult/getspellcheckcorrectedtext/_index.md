---
title: GetSpellCheckCorrectedText
second_title: Aspose.OCR for .NET API Reference
description: Corrects text replaces misspelled words.
type: docs
weight: 90
url: /net/aspose.ocr/recognitionresult/getspellcheckcorrectedtext/
---
## RecognitionResult.GetSpellCheckCorrectedText method

Corrects text (replaces misspelled words).

```csharp
public string GetSpellCheckCorrectedText(SpellCheckLanguage language = SpellCheckLanguage.Eng, 
    string dictionaryPath = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| language | SpellCheckLanguage | Dictionary to use. |
| dictionaryPath | String | Optionally. Full path to the user dictionary (frequency dictionary). Dictionary file format: Plain text file in UTF-8 encoding. Word and Word Frequency are separated by space or tab.Per default, the word is expected in the first column and the frequency in the second column. Every word-frequency-pair in a separate line.A line is defined as a sequence of characters followed by a line feed ("\n"), a carriage return ("\r"), or a carriage return immediately followed by a line feed("\r\n"). Every word is expected to be in lower case. |

### Return Value

Text with replaced words.

### See Also

* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
