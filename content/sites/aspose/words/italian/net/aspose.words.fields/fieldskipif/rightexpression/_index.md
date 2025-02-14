---
title: RightExpression
second_title: Aspose.Words per .NET API Reference
description: Ottiene o imposta la parte destra dellespressione di confronto.
type: docs
weight: 40
url: /it/net/aspose.words.fields/fieldskipif/rightexpression/
---
## FieldSkipIf.RightExpression property

Ottiene o imposta la parte destra dell'espressione di confronto.

```csharp
public string RightExpression { get; set; }
```

### Esempi

Mostra come saltare le pagine in una stampa unione utilizzando il campo SKIPIF.

```csharp
Document doc = new Document();
DocumentBuilder builder = new DocumentBuilder(doc);

// Inserisce un campo SKIPIF. Se la riga corrente di un'operazione di stampa unione soddisfa la condizione
// quale stato delle espressioni di questo campo, quindi l'operazione di stampa unione interrompe la riga corrente,
// Elimina il documento di unione corrente, quindi passa immediatamente alla riga successiva per iniziare il documento di unione successivo.
FieldSkipIf fieldSkipIf = (FieldSkipIf) builder.InsertField(FieldType.FieldSkipIf, true);

// Sposta il builder nel separatore del campo SKIPIF in modo da poter inserire un MERGEFIELD all'interno del campo SKIPIF.
builder.MoveTo(fieldSkipIf.Separator);
FieldMergeField fieldMergeField = (FieldMergeField)builder.InsertField(FieldType.FieldMergeField, true);
fieldMergeField.FieldName = "Department";

// Il MERGEFIELD fa riferimento alla colonna "Reparto" nella nostra tabella dati. Se una riga da quella tabella
// ha un valore di "HR" nella sua colonna "Department", quindi questa riga soddisferà la condizione.
fieldSkipIf.LeftExpression = "=";
fieldSkipIf.RightExpression = "HR";

// Aggiungi contenuto al nostro documento, crea l'origine dati ed esegui la stampa unione.
builder.MoveToDocumentEnd();
builder.Write("Dear ");
fieldMergeField = (FieldMergeField)builder.InsertField(FieldType.FieldMergeField, true);
fieldMergeField.FieldName = "Name";
builder.Writeln(", ");

 // Questa tabella ha tre righe e una di esse soddisfa le condizioni del nostro campo SKIPIF.
// La stampa unione produrrà due pagine.
DataTable table = new DataTable("Employees");
table.Columns.Add("Name");
table.Columns.Add("Department");
table.Rows.Add("John Doe", "Sales");
table.Rows.Add("Jane Doe", "Accounting");
table.Rows.Add("John Cardholder", "HR");

doc.MailMerge.Execute(table);
doc.Save(ArtifactsDir + "Field.SKIPIF.docx");
```

Mostra come utilizzare i campi MERGEREC e MERGESEQ per numerare e contare i record di stampa unione nei documenti di output di una stampa unione.

```csharp
Document doc = new Document();
DocumentBuilder builder = new DocumentBuilder(doc);

builder.Write("Dear ");
FieldMergeField fieldMergeField = (FieldMergeField)builder.InsertField(FieldType.FieldMergeField, true);
fieldMergeField.FieldName = "Name";
builder.Writeln(",");

// Un campo MERGEREC stamperà il numero di riga dei dati da unire in ogni documento di output di unione.
builder.Write("\nRow number of record in data source: ");
FieldMergeRec fieldMergeRec = (FieldMergeRec)builder.InsertField(FieldType.FieldMergeRec, true);

Assert.AreEqual(" MERGEREC ", fieldMergeRec.GetFieldCode());

// Un campo MERGESEQ conteggerà il numero di unioni riuscite e stamperà il valore corrente su ciascuna rispettiva pagina.
// Se una stampa unione non salta righe e non richiama campi SKIP/SKIPIF/NEXT/NEXTIF, tutte le unioni hanno esito positivo.
// I campi MERGESEQ e MERGEREC visualizzeranno gli stessi risultati della stampa unione riuscita.
builder.Write("\nSuccessful merge number: ");
FieldMergeSeq fieldMergeSeq = (FieldMergeSeq)builder.InsertField(FieldType.FieldMergeSeq, true);

Assert.AreEqual(" MERGESEQ ", fieldMergeSeq.GetFieldCode());

// Inserisci un campo SKIPIF, che salterà un'unione se il nome è "John Doe".
FieldSkipIf fieldSkipIf = (FieldSkipIf)builder.InsertField(FieldType.FieldSkipIf, true);
builder.MoveTo(fieldSkipIf.Separator);
fieldMergeField = (FieldMergeField)builder.InsertField(FieldType.FieldMergeField, true);
fieldMergeField.FieldName = "Name";
fieldSkipIf.LeftExpression = "=";
fieldSkipIf.RightExpression = "John Doe";

// Crea un'origine dati con 3 righe, una delle quali con "John Doe" come valore per la colonna "Nome".
// Poiché un campo SKIPIF verrà attivato una volta da quel valore, l'output della nostra stampa unione avrà 2 pagine anziché 3.
// A pagina 1, i campi MERGESEQ e MERGEREC visualizzeranno entrambi "1".
// A pagina 2, il campo MERGEREC visualizzerà "3" e il campo MERGERESEQ visualizzerà "2".
DataTable table = new DataTable("Employees");
table.Columns.Add("Name");
table.Rows.Add(new[] { "Jane Doe" });
table.Rows.Add(new[] { "John Doe" });
table.Rows.Add(new[] { "Joe Bloggs" });

doc.MailMerge.Execute(table);
doc.Save(ArtifactsDir + "Field.MERGEREC.MERGESEQ.docx");
```

### Guarda anche

* class [FieldSkipIf](../../fieldskipif)
* spazio dei nomi [Aspose.Words.Fields](../../fieldskipif)
* assemblea [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
