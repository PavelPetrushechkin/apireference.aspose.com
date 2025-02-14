---
title: Save
second_title: Referencia de API de Aspose.OCR para .NET
description: Guarda el documento como texto sin formato PDF o documento de Microsoft Word.
type: docs
weight: 120
url: /es/net/aspose.ocr/recognitionresult/save/
---
## Save(string, SaveFormat, bool, SpellCheckLanguage, string) {#save_1}

Guarda el documento como texto sin formato, PDF o documento de Microsoft Word.

```csharp
public void Save(string fullFileName, SaveFormat saveFormat, bool applySpellingCorrection = false, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fullFileName | String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | SaveFormat | Formato del documento (Docx, Txt, Pdf). |
| applySpellingCorrection | Boolean | Configure verdadero para corregir las palabras mal escritas en caso de que las tenga en su resultado de reconocimiento. |
| language | SpellCheckLanguage | Diccionario para el corrector ortográfico (opcional). |
| dictionaryPath | String | Opcionalmente. Ruta completa al diccionario del usuario en formato .txt. El formato es [palabra - espacio - frecuencia (número)]. Ejemplo: el 23135851162\nque 3400031103\n |

### Ver también

* enum [SaveFormat](../../saveformat)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* espacio de nombres [Aspose.OCR](../../recognitionresult)
* asamblea [Aspose.OCR](../../../)

---

## Save(MemoryStream, SaveFormat, bool, SpellCheckLanguage, string) {#save}

Guarda el documento como texto sin formato, PDF o documento de Microsoft Word.

```csharp
public void Save(MemoryStream stream, SaveFormat saveFormat, bool applySpellingCorrection = false, 
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | MemoryStream | MemoryStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | SaveFormat | Formato del documento (Docx, Txt, Pdf). |
| applySpellingCorrection | Boolean | Configure verdadero para corregir las palabras mal escritas en caso de que las tenga en su resultado de reconocimiento. |
| language | SpellCheckLanguage | Diccionario para el corrector ortográfico (opcional). |
| dictionaryPath | String | Opcionalmente. Ruta completa al diccionario del usuario en formato .txt. El formato es [palabra - espacio - frecuencia (número)]. Ejemplo: el 23135851162\nque 3400031103\n |

### Ver también

* enum [SaveFormat](../../saveformat)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* espacio de nombres [Aspose.OCR](../../recognitionresult)
* asamblea [Aspose.OCR](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.OCR.dll -->
