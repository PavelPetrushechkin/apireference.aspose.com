---
title: Print
second_title: Aspose.Note per .NET API Reference
description: Stampa il documento utilizzando la stampante predefinita.
type: docs
weight: 130
url: /it/net/aspose.note/document/print/
---
## Print() {#print}

Stampa il documento utilizzando la stampante predefinita.

```csharp
public void Print()
```

### Esempi

Mostra come inviare un documento a una stampante utilizzando la finestra di dialogo standard di Windows con le opzioni predefinite.

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

var document = new Aspose.Note.Document(dataDir + "Aspose.one");

document.Print();
```

Mostra come inviare un documento a una stampante utilizzando la finestra di dialogo standard di Windows con le opzioni specificate.

```csharp
// Il percorso della directory dei documenti.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

var document = new Aspose.Note.Document(dataDir + "Aspose.one");

var printerSettings = new PrinterSettings() { FromPage = 0, ToPage = 10 };
printerSettings.DefaultPageSettings.Landscape = true;
printerSettings.DefaultPageSettings.Margins = new System.Drawing.Printing.Margins(50, 50, 150, 50);

document.Print(new PrintOptions()
               {
                   PrinterSettings = printerSettings,
                   Resolution = 1200,
                   PageSplittingAlgorithm = new KeepSolidObjectsAlgorithm(),
                   DocumentName = "Test.one"
               });
```

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Note](../../document)
* assemblea [Aspose.Note](../../../)

---

## Print(PrintOptions) {#print_1}

Stampa il documento utilizzando la stampante predefinita.

```csharp
public void Print(PrintOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | PrintOptions | Opzioni utilizzate per stampare un documento. Può essere nullo. |

### Guarda anche

* class [PrintOptions](../../../aspose.note.saving/printoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Note](../../document)
* assemblea [Aspose.Note](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
