---
title: CopyStylesFromTemplate
second_title: Aspose.Words per .NET API Reference
description: Copia gli stili dal modello specificato in un documento.
type: docs
weight: 550
url: /it/net/aspose.words/document/copystylesfromtemplate/
---
## CopyStylesFromTemplate(string) {#copystylesfromtemplate_1}

Copia gli stili dal modello specificato in un documento.

```csharp
public void CopyStylesFromTemplate(string template)
```

### Osservazioni

Quando gli stili vengono copiati da un modello a un documento, gli stili con nomi simili nel documento vengono ridefiniti per corrispondere alle descrizioni degli stili nel modello. Gli stili univoci dal modello vengono copiati nel documento. Gli stili univoci nel documento rimangono intatti.

### Esempi

Mostra come copiare gli stili da un documento all'altro.

```csharp
// Crea un documento, quindi aggiungi gli stili che copieremo in un altro documento.
Document template = new Document();

Style style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle1");
style.Font.Name = "Times New Roman";
style.Font.Color = Color.Navy;

style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle2");
style.Font.Name = "Arial";
style.Font.Color = Color.DeepSkyBlue;

style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle3");
style.Font.Name = "Courier New";
style.Font.Color = Color.RoyalBlue;

Assert.AreEqual(7, template.Styles.Count);

// Crea un documento in cui copieremo gli stili.
Document target = new Document();

// Crea uno stile con lo stesso nome di uno stile dal documento modello e aggiungilo al documento di destinazione.
style = target.Styles.Add(StyleType.Paragraph, "TemplateStyle3");
style.Font.Name = "Calibri";
style.Font.Color = Color.Orange;

Assert.AreEqual(5, target.Styles.Count);

// Esistono due modi per chiamare il metodo per copiare tutti gli stili da un documento all'altro.
// 1 - Passaggio dell'oggetto documento modello:
target.CopyStylesFromTemplate(template);

// La copia degli stili aggiunge tutti gli stili dal documento modello alla destinazione
// e sovrascrive gli stili esistenti con lo stesso nome.
Assert.AreEqual(7, target.Styles.Count);

Assert.AreEqual("Courier New", target.Styles["TemplateStyle3"].Font.Name);
Assert.AreEqual(Color.RoyalBlue.ToArgb(), target.Styles["TemplateStyle3"].Font.Color.ToArgb());

// 2 - Passaggio del nome file di sistema locale di un documento modello:
target.CopyStylesFromTemplate(MyDir + "Rendering.docx");

Assert.AreEqual(21, target.Styles.Count);
```

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Words](../../document)
* assemblea [Aspose.Words](../../../)

---

## CopyStylesFromTemplate(Document) {#copystylesfromtemplate}

Copia gli stili dal modello specificato in un documento.

```csharp
public void CopyStylesFromTemplate(Document template)
```

### Osservazioni

Quando gli stili vengono copiati da un modello a un documento, gli stili con nomi simili nel documento vengono ridefiniti per corrispondere alle descrizioni degli stili nel modello. Gli stili univoci dal modello vengono copiati nel documento. Gli stili univoci nel documento rimangono intatti.

### Esempi

Mostra come copiare gli stili dal modello a un documento tramite Documento.

```csharp
Document template = new Document(MyDir + "Rendering.docx");
Document target = new Document(MyDir + "Document.docx");

target.CopyStylesFromTemplate(template);
```

Mostra come copiare gli stili da un documento all'altro.

```csharp
// Crea un documento, quindi aggiungi gli stili che copieremo in un altro documento.
Document template = new Document();

Style style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle1");
style.Font.Name = "Times New Roman";
style.Font.Color = Color.Navy;

style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle2");
style.Font.Name = "Arial";
style.Font.Color = Color.DeepSkyBlue;

style = template.Styles.Add(StyleType.Paragraph, "TemplateStyle3");
style.Font.Name = "Courier New";
style.Font.Color = Color.RoyalBlue;

Assert.AreEqual(7, template.Styles.Count);

// Crea un documento in cui copieremo gli stili.
Document target = new Document();

// Crea uno stile con lo stesso nome di uno stile dal documento modello e aggiungilo al documento di destinazione.
style = target.Styles.Add(StyleType.Paragraph, "TemplateStyle3");
style.Font.Name = "Calibri";
style.Font.Color = Color.Orange;

Assert.AreEqual(5, target.Styles.Count);

// Esistono due modi per chiamare il metodo per copiare tutti gli stili da un documento all'altro.
// 1 - Passaggio dell'oggetto documento modello:
target.CopyStylesFromTemplate(template);

// La copia degli stili aggiunge tutti gli stili dal documento modello alla destinazione
// e sovrascrive gli stili esistenti con lo stesso nome.
Assert.AreEqual(7, target.Styles.Count);

Assert.AreEqual("Courier New", target.Styles["TemplateStyle3"].Font.Name);
Assert.AreEqual(Color.RoyalBlue.ToArgb(), target.Styles["TemplateStyle3"].Font.Color.ToArgb());

// 2 - Passaggio del nome file di sistema locale di un documento modello:
target.CopyStylesFromTemplate(MyDir + "Rendering.docx");

Assert.AreEqual(21, target.Styles.Count);
```

### Guarda anche

* class [Document](../../document)
* spazio dei nomi [Aspose.Words](../../document)
* assemblea [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
