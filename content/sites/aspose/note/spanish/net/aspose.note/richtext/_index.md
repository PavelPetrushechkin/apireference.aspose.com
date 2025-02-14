---
title: RichText
second_title: Aspose.Note para la referencia de la API de .NET
description: Representa un texto enriquecido.
type: docs
weight: 510
url: /es/net/aspose.note/richtext/
---
## RichText class

Representa un texto enriquecido.

```csharp
public sealed class RichText : Node, IEnumerable<char>, IOutlineElementChildNode, ITaggable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RichText](richtext#constructor)() | Inicializa una nueva instancia del[`RichText`](../richtext) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.note/richtext/alignment) { get; set; } | Obtiene o establece la alineación. |
| [Document](../../aspose.note/node/document) { get; } | Obtiene el documento del nodo. |
| virtual [IsComposite](../../aspose.note/node/iscomposite) { get; } | Obtiene un valor que indica si este nodo es compuesto. Si es verdadero, el nodo puede tener nodos secundarios. |
| [LastModifiedTime](../../aspose.note/richtext/lastmodifiedtime) { get; set; } | Obtiene o establece la hora de última modificación. |
| [Length](../../aspose.note/richtext/length) { get; } | Obtiene la longitud del texto. |
| [LineSpacing](../../aspose.note/richtext/linespacing) { get; set; } | Obtiene o establece el interlineado. |
| [NextSibling](../../aspose.note/node/nextsibling) { get; } | Obtiene el siguiente nodo en el mismo nivel de árbol de nodos. |
| [NodeType](../../aspose.note/node/nodetype) { get; } | Obtiene el tipo de nodo. |
| [ParagraphStyle](../../aspose.note/richtext/paragraphstyle) { get; set; } | Obtiene o establece el estilo de párrafo. Esta configuración se usa si no hay un objeto TextStyle coincidente enStyles colección este objeto no especifica una configuración necesaria. |
| [ParentNode](../../aspose.note/node/parentnode) { get; } | Obtiene el nodo padre. |
| [PreviousSibling](../../aspose.note/node/previoussibling) { get; } | Obtiene el nodo anterior en el mismo nivel de árbol de nodos. |
| [SpaceAfter](../../aspose.note/richtext/spaceafter) { get; set; } | Obtiene o establece la cantidad mínima de espacio después de. |
| [SpaceBefore](../../aspose.note/richtext/spacebefore) { get; set; } | Obtiene o establece la cantidad mínima de espacio antes. |
| [Tags](../../aspose.note/richtext/tags) { get; } | Obtiene la lista de todas las etiquetas de un párrafo. |
| [Text](../../aspose.note/richtext/text) { get; set; } | Obtiene o establece el texto. La cadena NO DEBE contener ningún carácter del valor 10 (salto de línea). |
| [TextRuns](../../aspose.note/richtext/textruns) { get; } | Obtiene la colección de ejecuciones de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Accept](../../aspose.note/richtext/accept)(DocumentVisitor) | Acepta al visitante del nodo. |
| [Append](../../aspose.note/richtext/append#append)(string) | Agrega una cadena al último rango de texto. |
| [Append](../../aspose.note/richtext/append#append_1)(string, TextStyle) | Agrega una cadena al final. |
| [AppendFront](../../aspose.note/richtext/appendfront#appendfront)(string) | Agrega una cadena al frente del primer rango de texto. |
| [AppendFront](../../aspose.note/richtext/appendfront#appendfront_1)(string, TextStyle) | Agrega una cadena al frente. |
| [Clear](../../aspose.note/richtext/clear)() | Borra el contenido de esta instancia. |
| [GetEnumerator](../../aspose.note/richtext/getenumerator)() | Devuelve un enumerador que itera a través de los caracteres de este objeto RichText. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof)(char) | Devuelve el índice de base cero de la primera aparición del carácter Unicode especificado en esta cadena. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_3)(string) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en esta instancia. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_1)(char, int) | Devuelve el índice de base cero de la primera aparición del carácter Unicode especificado en esta cadena. La búsqueda comienza en una posición de carácter especificada. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_4)(string, int) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en esta instancia. La búsqueda comienza en una posición de carácter especificada. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_8)(string, StringComparison) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en la instancia actual. Un parámetro especifica el tipo de búsqueda que se utilizará para la cadena especificada. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_2)(char, int, int) | Devuelve el índice de base cero de la primera aparición del carácter especificado en esta instancia. La búsqueda comienza en una posición de carácter específica y examina un número específico de posiciones de carácter. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_5)(string, int, int) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en esta instancia. La búsqueda comienza en una posición de carácter específica y examina un número específico de posiciones de carácter. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_7)(string, int, StringComparison) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en la instancia actual. Los parámetros especifican la posición inicial de búsqueda en la cadena actual y el tipo de búsqueda que se utilizará para la cadena especificada. |
| [IndexOf](../../aspose.note/richtext/indexof#indexof_6)(string, int, int, StringComparison) | Devuelve el índice de base cero de la primera aparición de la cadena especificada en la instancia actual. |
| [Insert](../../aspose.note/richtext/insert#insert)(int, string) | Inserta una cadena especificada en una posición de índice especificada en esta instancia. |
| [Insert](../../aspose.note/richtext/insert#insert_1)(int, string, TextStyle) | Inserta una cadena especificada con un estilo especificado en una posición de índice especificada en esta instancia. |
| [Remove](../../aspose.note/richtext/remove#remove)(int) | Elimina todos los caracteres en la instancia actual, comenzando en una posición específica y continuando hasta la última posición. |
| [Remove](../../aspose.note/richtext/remove#remove_1)(int, int) | Elimina el número especificado de caracteres en la instancia actual comenzando en una posición especificada. |
| [Replace](../../aspose.note/richtext/replace#replace)(char, char) | Reemplaza todas las apariciones de un carácter Unicode especificado en esta instancia con otro carácter Unicode especificado. |
| [Replace](../../aspose.note/richtext/replace#replace_1)(string, string) | Reemplaza todas las apariciones de una cadena especificada en la instancia actual con otra cadena especificada. |
| [Replace](../../aspose.note/richtext/replace#replace_2)(string, string, TextStyle) | Reemplaza todas las apariciones de una cadena especificada en la instancia actual con otra cadena especificada en el estilo especificado. |
| [Trim](../../aspose.note/richtext/trim#trim)() | Elimina todos los espacios en blanco iniciales y finales. |
| [Trim](../../aspose.note/richtext/trim#trim_1)(char) | Elimina todas las instancias iniciales y finales de un carácter. |
| [Trim](../../aspose.note/richtext/trim#trim_2)(params char[]) | Elimina todas las ocurrencias iniciales y finales de un conjunto de caracteres especificado en una matriz. |
| [TrimEnd](../../aspose.note/richtext/trimend#trimend)() | Elimina todos los espacios en blanco finales. |
| [TrimEnd](../../aspose.note/richtext/trimend#trimend_1)(char) | Elimina todas las ocurrencias finales de un carácter. |
| [TrimEnd](../../aspose.note/richtext/trimend#trimend_2)(params char[]) | Elimina todas las ocurrencias finales de un conjunto de caracteres especificado en una matriz. |
| [TrimStart](../../aspose.note/richtext/trimstart#trimstart)() | Elimina todos los espacios en blanco iniciales. |
| [TrimStart](../../aspose.note/richtext/trimstart#trimstart_1)(char) | Elimina todas las ocurrencias iniciales de un carácter específico. |
| [TrimStart](../../aspose.note/richtext/trimstart#trimstart_2)(params char[]) | Elimina todas las ocurrencias iniciales de un conjunto de caracteres especificado en una matriz. |

### Ejemplos

Muestra cómo obtener todo el texto del documento.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Text();

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Recuperar texto
string text = string.Join(Environment.NewLine, oneFile.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

// Imprimir texto en la pantalla de salida
Console.WriteLine(text);
```

Muestra cómo obtener todo el texto de la página.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Text();

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Obtener la lista de nodos de la página
var page = oneFile.GetChildNodes<Page>().FirstOrDefault();

if (page != null)
{
    // Recuperar texto
    string text = string.Join(Environment.NewLine, page.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;
    // Imprimir texto en la pantalla de salida
    Console.WriteLine(text);
}
```

Destaquemos los títulos de las páginas entre otros encabezados aumentando el tamaño de la fuente.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Cargue el documento en Aspose.Note.
Document document = new Document(dataDir + "Aspose.one");

// Iterar a través de los títulos de la página.
foreach (var title in document.Select(e => e.Title.TitleText))
{
    title.ParagraphStyle.FontSize = 24;
    title.ParagraphStyle.IsBold = true;

    foreach (var run in title.TextRuns)
    {
        run.Style.FontSize = 24;
        run.Style.IsBold = true;
    }
}

document.Save(Path.Combine(dataDir, "ChangePageTitleStyle.pdf"));
```

Muestra cómo obtener texto de la fila de cada tabla.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tables();

// Cargue el documento en Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Obtenga una lista de los nodos de la tabla
IList<Table> nodes = document.GetChildNodes<Table>();

foreach (Table table in nodes)
{
    // Iterar a través de las filas de la tabla
    foreach (TableRow row in table)
    {
        // Recuperar texto
        string text = string.Join(Environment.NewLine, row.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

        // Imprimir texto en la pantalla de salida
        Console.WriteLine(text);
    }
}
```

Muestra cómo obtener texto de una tabla.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tables();

// Cargue el documento en Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Obtenga una lista de los nodos de la tabla
IList<Table> nodes = document.GetChildNodes<Table>();

// Establecer el conteo de la mesa
int tblCount = 0;

foreach (Table table in nodes)
{
    tblCount++;
    Console.WriteLine("table # " + tblCount);

    // Recuperar texto
    string text = string.Join(Environment.NewLine, table.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

    // Imprimir texto en la pantalla de salida
    Console.WriteLine(text);
}
```

Resaltemos los últimos cambios del texto resaltando.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Cargue el documento en Aspose.Note.
Document document = new Document(dataDir + "Aspose.one");

// Obtenga los nodos RichText modificados la semana pasada.
var richTextNodes = document.GetChildNodes<RichText>().Where(e => e.LastModifiedTime >= DateTime.Today.Subtract(TimeSpan.FromDays(7)));

foreach (var node in richTextNodes)
{
    // Establecer color de resaltado
    node.ParagraphStyle.Highlight = Color.DarkGreen;
    foreach (var run in node.TextRuns)
    {
        // Establecer color de resaltado
        run.Style.Highlight = Color.DarkSeaGreen;
    }
}

document.Save(Path.Combine(dataDir, "HighlightAllRecentChanges.pdf"));
```

Muestra cómo establecer un título para una página.

```csharp
string dataDir = RunExamples.GetDataDir_Text();
string outputPath = dataDir + "CreateTitleMsStyle_out.one";

var doc = new Document();
var page = new Page(doc);

page.Title = new Title(doc)
{
    TitleText = new RichText(doc)
    {
        Text = "Title text.",
        ParagraphStyle = ParagraphStyle.Default
    },
    TitleDate = new RichText(doc)
    {
        Text = new DateTime(2011, 11, 11).ToString("D", CultureInfo.InvariantCulture),
        ParagraphStyle = ParagraphStyle.Default
    },
    TitleTime = new RichText(doc)
    {
        Text = "12:34",
        ParagraphStyle = ParagraphStyle.Default
    }
};

doc.AppendChildLast(page);

doc.Save(outputPath);
```

Establecer el idioma de prueba para un texto.

```csharp
var document = new Document();
var page = new Page();
var outline = new Outline();
var outlineElem = new OutlineElement();

var text = new RichText() { ParagraphStyle = ParagraphStyle.Default };
text.Append("United States", new TextStyle() { Language = CultureInfo.GetCultureInfo("en-US") })
    .Append(" Germany", new TextStyle() { Language = CultureInfo.GetCultureInfo("de-DE") })
    .Append(" China", new TextStyle() { Language = CultureInfo.GetCultureInfo("zh-CN") });

outlineElem.AppendChildLast(text);
outline.AppendChildLast(outlineElem);
page.AppendChildLast(outline);
document.AppendChildLast(page);

document.Save(Path.Combine(RunExamples.GetDataDir_Text(), "SetProofingLanguageForText.one"));
```

Muestra cómo pasar por todas las páginas y hacer un reemplazo en el texto.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Text();

Dictionary<string, string> replacements = new Dictionary<string, string>();
replacements.Add("Some task here", "New Text Here");

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

// Obtener todos los nodos RichText
IList<RichText> textNodes = oneFile.GetChildNodes<RichText>();

foreach (RichText richText in textNodes)
{
    foreach (KeyValuePair<string, string> kvp in replacements)
    {
        // Reemplazar el texto de una forma
        richText.Replace(kvp.Key, kvp.Value);
    }
}

dataDir = dataDir + "ReplaceTextOnAllPages_out.pdf";

// Guardar en cualquier formato de archivo compatible
oneFile.Save(dataDir, SaveFormat.Pdf);
```

Manipular por formato de texto usando estilo de párrafo.

```csharp
var document = new Document();
var page = new Page();
var outline = new Outline();
var outlineElem = new OutlineElement();

var text = new RichText() { ParagraphStyle = new ParagraphStyle() { FontName = "Courier New", FontSize = 20 } }
                .Append($"DefaultParagraphFontAndSize{Environment.NewLine}")
                .Append($"OnlyDefaultParagraphFont{Environment.NewLine}", new TextStyle() { FontSize = 14 })
                .Append("OnlyDefaultParagraphFontSize", new TextStyle() { FontName = "Verdana" });

outlineElem.AppendChildLast(text);
outline.AppendChildLast(outlineElem);
page.AppendChildLast(outline);
document.AppendChildLast(page);

document.Save(Path.Combine(RunExamples.GetDataDir_Text(), "SetDefaultParagraphStyle.one"));
```

Muestra cómo obtener texto de las celdas de una tabla.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tables();

// Cargue el documento en Aspose.Note.
Document document = new Document(dataDir + "Sample1.one");

// Obtenga una lista de los nodos de la tabla
IList<Table> nodes = document.GetChildNodes<Table>();        

foreach (Table table in nodes)
{
    // Iterar a través de las filas de la tabla
    foreach (TableRow row in table)
    {
        // Obtener la lista de nodos TableCell
        // Iterar a través de las celdas de la tabla
        foreach (TableCell cell in row)
        {
            // Recuperar texto
            string text = string.Join(Environment.NewLine, cell.GetChildNodes<RichText>().Select(e => e.Text)) + Environment.NewLine;

            // Imprimir texto en la pantalla de salida
            Console.WriteLine(text);
        }
    }
}
```

Muestra cómo pasar el texto de la página y hacer un reemplazo.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Text();

Dictionary<string, string> replacements = new Dictionary<string, string>();
replacements.Add("voice over", "voice over new text");

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "Aspose.one");

IList<Page> pageNodes = oneFile.GetChildNodes<Page>();

// Obtener todos los nodos RichText
IList<RichText> textNodes = pageNodes[0].GetChildNodes<RichText>();

foreach (RichText richText in textNodes)
{
    foreach (KeyValuePair<string, string> kvp in replacements)
    {
        // Reemplazar el texto de una forma
        richText.Replace(kvp.Key, kvp.Value);
    }
}

// Guardar en cualquier formato de archivo compatible
dataDir = dataDir + "ReplaceTextOnParticularPage_out.pdf";
oneFile.Save(dataDir, SaveFormat.Pdf);
```

Muestra cómo crear un documento y guardarlo en formato html usando las opciones predeterminadas.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Inicializa el documento de OneNote
Document doc = new Document();
Page page = doc.AppendChildLast(new Page());

// Estilo predeterminado para todo el texto del documento.
ParagraphStyle textStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };
page.Title = new Title()
                 {
                     TitleText = new RichText() { Text = "Title text.", ParagraphStyle = textStyle },
                     TitleDate = new RichText() { Text = new DateTime(2011, 11, 11).ToString("D", CultureInfo.InvariantCulture), ParagraphStyle = textStyle },
                     TitleTime = new RichText() { Text = "12:34", ParagraphStyle = textStyle }
                 };

// Guardar en formato HTML
dataDir = dataDir + "CreateOneNoteDocAndSaveToHTML_out.html";
doc.Save(dataDir);
```

Muestra cómo agregar un nuevo párrafo con etiqueta.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tags();

// Crear un objeto de la clase Documento
Document doc = new Document();

// Inicializar objeto de clase de página
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// Inicializa el objeto de la clase Esquema
Outline outline = new Outline(doc);

// Inicializa el objeto de la clase OutlineElement
OutlineElement outlineElem = new OutlineElement(doc);
ParagraphStyle textStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };
RichText text = new RichText(doc) { Text = "OneNote text.", ParagraphStyle = textStyle };
text.Tags.Add(NoteTag.CreateYellowStar());

// Agregar nodo de texto
outlineElem.AppendChildLast(text);

// Agregar nodo de elemento de esquema
outline.AppendChildLast(outlineElem);

// Agregar nodo de esquema
page.AppendChildLast(outline);

// Añadir nodo de página
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "AddTextNodeWithTag_out.one";
doc.Save(dataDir);
```

Muestra cómo crear un documento y guardarlo en un rango de páginas especificado en formato html.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Inicializa el documento de OneNote
Document doc = new Document();

Page page = doc.AppendChildLast(new Page());

// Estilo predeterminado para todo el texto del documento.
ParagraphStyle textStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };
page.Title = new Title()
             {
                 TitleText = new RichText() { Text = "Title text.", ParagraphStyle = textStyle },
                 TitleDate = new RichText() { Text = new DateTime(2011, 11, 11).ToString("D", CultureInfo.InvariantCulture), ParagraphStyle = textStyle },
                 TitleTime = new RichText() { Text = "12:34", ParagraphStyle = textStyle }
             };

// Guardar en formato HTML
dataDir = dataDir + "CreateAndSavePageRange_out.html";
doc.Save(dataDir, new HtmlSaveOptions
                  {
                      PageCount = 1,
                      PageIndex = 0
                  });
```

Muestra cómo acceder a los detalles de una etiqueta.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tags();

// Cargue el documento en Aspose.Note.
Document oneFile = new Document(dataDir + "TagFile.one");

// Obtener todos los nodos RichText
IList<RichText> nodes = oneFile.GetChildNodes<RichText>();

// Iterar a través de cada nodo
foreach (RichText richText in nodes)
{
    var tags = richText.Tags.OfType<NoteTag>();
    if (tags.Any())
    {
        Console.WriteLine($"Text: {richText.Text}");
        foreach (var noteTag in tags)
        {
            // Recuperar propiedades
            Console.WriteLine($"    Completed Time: {noteTag.CompletedTime}");
            Console.WriteLine($"    Create Time: {noteTag.CreationTime}");
            Console.WriteLine($"    Font Color: {noteTag.FontColor}");
            Console.WriteLine($"    Status: {noteTag.Status}");
            Console.WriteLine($"    Label: {noteTag.Label}");
            Console.WriteLine($"    Icon: {noteTag.Icon}");
            Console.WriteLine($"    High Light: {noteTag.Highlight}");
        }
    }
}
```

Muestra cómo crear un documento con un texto.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_LoadingAndSaving();

// Crear un objeto de la clase Documento
Document doc = new Document();

// Inicializar objeto de clase de página
Page page = new Page(doc);

// Inicializa el objeto de la clase Esquema
Outline outline = new Outline(doc);

// Inicializa el objeto de la clase OutlineElement
OutlineElement outlineElem = new OutlineElement(doc);

// Inicializa el objeto de la clase TextStyle y establece las propiedades de formato
ParagraphStyle textStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };

// Inicializa el objeto de la clase RichText y aplica el estilo de texto
RichText text = new RichText(doc) { Text = "Hello OneNote text!", ParagraphStyle = textStyle };

// Agregar nodo de texto enriquecido
outlineElem.AppendChildLast(text);

// Agregar nodo de elemento de esquema
outline.AppendChildLast(outlineElem);

// Añadir nodo Esquema
page.AppendChildLast(outline);

// Agregar nodo de página
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "CreateDocWithSimpleRichText_out.one";
doc.Save(dataDir);
```

Muestra cómo insertar una nueva lista con numeración china.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Inicializa el documento de OneNote
Aspose.Note.Document doc = new Aspose.Note.Document();

// Inicializar la página de OneNote
Aspose.Note.Page page = new Aspose.Note.Page(doc);
Outline outline = new Outline(doc);

// Aplicar la configuración de estilo de texto
ParagraphStyle defaultStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };

// Los números en el mismo esquema se incrementan automáticamente.
OutlineElement outlineElem1 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.ChineseCounting, "Arial", 10) };
RichText text1 = new RichText(doc) { Text = "First", ParagraphStyle = defaultStyle };
outlineElem1.AppendChildLast(text1);

//------------------------
OutlineElement outlineElem2 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.ChineseCounting, "Arial", 10) };
RichText text2 = new RichText(doc) { Text = "Second", ParagraphStyle = defaultStyle };
outlineElem2.AppendChildLast(text2);

//------------------------
OutlineElement outlineElem3 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.ChineseCounting, "Arial", 10) };
RichText text3 = new RichText(doc) { Text = "Third", ParagraphStyle = defaultStyle };
outlineElem3.AppendChildLast(text3);

//------------------------
outline.AppendChildLast(outlineElem1);
outline.AppendChildLast(outlineElem2);
outline.AppendChildLast(outlineElem3);
page.AppendChildLast(outline);
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "InsertChineseNumberList_out.one"; 
doc.Save(dataDir);
```

Muestra cómo insertar nuevas listas con viñetas.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Crear un objeto de la clase Documento
Aspose.Note.Document doc = new Aspose.Note.Document();

// Inicializar objeto de clase de página
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// Inicializa el objeto de la clase Esquema
Outline outline = new Outline(doc);

// Inicializa el objeto de la clase TextStyle y establece las propiedades de formato
ParagraphStyle defaultStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };

// Inicializar objetos de la clase OutlineElement y aplicar viñetas
OutlineElement outlineElem1 = new OutlineElement(doc) { NumberList = new NumberList("*", "Arial", 10) };

// Inicializa el objeto de la clase RichText y aplica el estilo de texto
RichText text1 = new RichText(doc) { Text = "First", ParagraphStyle = defaultStyle };
outlineElem1.AppendChildLast(text1);

OutlineElement outlineElem2 = new OutlineElement(doc) { NumberList = new NumberList("*", "Arial", 10) };
RichText text2 = new RichText(doc) { Text = "Second", ParagraphStyle = defaultStyle };
outlineElem2.AppendChildLast(text2);

OutlineElement outlineElem3 = new OutlineElement(doc) { NumberList = new NumberList("*", "Arial", 10) };
RichText text3 = new RichText(doc) { Text = "Third", ParagraphStyle = defaultStyle };
outlineElem3.AppendChildLast(text3);

// Agregar elementos de contorno
outline.AppendChildLast(outlineElem1);
outline.AppendChildLast(outlineElem2);
outline.AppendChildLast(outlineElem3);

// Añadir nodo Esquema
page.AppendChildLast(outline);
// Agregar nodo de página
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "ApplyBulletsOnText_out.one"; 
doc.Save(dataDir);
```

Muestra cómo insertar una nueva lista con numeración.

```csharp
string dataDir = RunExamples.GetDataDir_Text();

// Crear un objeto de la clase Documento
Document doc = new Document();

// Inicializar objeto de clase de página
Aspose.Note.Page page = new Aspose.Note.Page(doc);

// Inicializa el objeto de la clase Esquema
Outline outline = new Outline(doc);

// Inicializa el objeto de la clase TextStyle y establece las propiedades de formato
ParagraphStyle defaultStyle = new ParagraphStyle { FontColor = Color.Black, FontName = "Arial", FontSize = 10 };

// Inicializar los objetos de la clase OutlineElement y aplicar la numeración
// Los números en el mismo esquema se incrementan automáticamente.
OutlineElement outlineElem1 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.DecimalNumbers, "Arial", 10) };
RichText text1 = new RichText(doc) { Text = "First", ParagraphStyle = defaultStyle };
outlineElem1.AppendChildLast(text1);

OutlineElement outlineElem2 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.DecimalNumbers, "Arial", 10) };
RichText text2 = new RichText(doc) { Text = "Second", ParagraphStyle = defaultStyle };
outlineElem2.AppendChildLast(text2);

OutlineElement outlineElem3 = new OutlineElement(doc) { NumberList = new NumberList("{0})", NumberFormat.DecimalNumbers, "Arial", 10) };
RichText text3 = new RichText(doc) { Text = "Third", ParagraphStyle = defaultStyle };
outlineElem3.AppendChildLast(text3);

// Agregar elementos de contorno
outline.AppendChildLast(outlineElem1);
outline.AppendChildLast(outlineElem2);
outline.AppendChildLast(outlineElem3);

// Añadir nodo Esquema
page.AppendChildLast(outline);

// Agregar nodo de página
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "ApplyNumberingOnText_out.one"; 
doc.Save(dataDir);
```

Muestra cómo preparar una plantilla para la reunión semanal.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tags();

// Crear un objeto de la clase Documento
var headerStyle = new ParagraphStyle() { FontName = "Calibri", FontSize = 16 };
var bodyStyle = new ParagraphStyle() { FontName = "Calibri", FontSize = 12 };

var d = new Document();
bool restartFlag = true;
var outline = d.AppendChildLast(new Page()
                                    {
                                        Title = new Title() { TitleText = new RichText() { Text = $"Weekly meeting {DateTime.Today:d}", ParagraphStyle = ParagraphStyle.Default } }
                                    })
               .AppendChildLast(new Outline() { VerticalOffset = 30, HorizontalOffset = 30 });

outline.AppendChildLast(new OutlineElement())
       .AppendChildLast(new RichText() { Text = "Important", ParagraphStyle = headerStyle });
foreach (var e in new[] { "First", "Second", "Third" })
{
    outline.AppendChildLast(new OutlineElement() { NumberList = CreateListNumberingStyle(bodyStyle, restartFlag) })
           .AppendChildLast(new RichText() { Text = e, ParagraphStyle = bodyStyle });
    restartFlag = false;
}

outline.AppendChildLast(new OutlineElement())
       .AppendChildLast(new RichText() { Text = "TO DO", ParagraphStyle = headerStyle, SpaceBefore = 15 });
restartFlag = true;
foreach (var e in new[] { "First", "Second", "Third" })
{
    outline.AppendChildLast(new OutlineElement() { NumberList = CreateListNumberingStyle(bodyStyle, restartFlag) })
           .AppendChildLast(new RichText() { Text = e, ParagraphStyle = bodyStyle, Tags = { NoteCheckBox.CreateBlueCheckBox() } });
    restartFlag = false;
}

d.Save(Path.Combine(dataDir, "meetingNotes.one"));
```

Muestra cómo vincular un hipervínculo a un texto.

```csharp
// La ruta al directorio de documentos.
string dataDir = RunExamples.GetDataDir_Tasks();

// Crear un objeto de la clase Documento
Document doc = new Document();

RichText titleText = new RichText() { ParagraphStyle = ParagraphStyle.Default }.Append("Title!");

Outline outline = new Outline()
                      {
                          MaxWidth = 200,
                          MaxHeight = 200,
                          VerticalOffset = 100,
                          HorizontalOffset = 100
                      };

TextStyle textStyleRed = new TextStyle
                             {
                                 FontColor = Color.Red,
                                 FontName = "Arial",
                                 FontSize = 10,
                             };

TextStyle textStyleHyperlink = new TextStyle
                                   {
                                       IsHyperlink = true,
                                       HyperlinkAddress = "www.google.com"
                                   };

RichText text = new RichText() { ParagraphStyle = ParagraphStyle.Default }
                    .Append("This is ", textStyleRed)
                    .Append("hyperlink", textStyleHyperlink)
                    .Append(". This text is not a hyperlink.", TextStyle.Default);

OutlineElement outlineElem = new OutlineElement();
outlineElem.AppendChildLast(text);

// Agregar elementos de contorno
outline.AppendChildLast(outlineElem);

// Inicializa el objeto de la clase Título
Title title = new Title() { TitleText = titleText };

// Inicializar objeto de clase de página
Page page = new Note.Page() { Title = title };

// Añadir nodo Esquema
page.AppendChildLast(outline);

// Agregar nodo de página
doc.AppendChildLast(page);

// Guardar documento de OneNote
dataDir = dataDir + "AddHyperlink_out.one";
doc.Save(dataDir);
```

### Ver también

* class [Node](../node)
* interface [IOutlineElementChildNode](../ioutlineelementchildnode)
* interface [ITaggable](../itaggable)
* espacio de nombres [Aspose.Note](../../aspose.note)
* asamblea [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
