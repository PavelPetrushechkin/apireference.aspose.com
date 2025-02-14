---
title: Warning
second_title: Aspose.Words for .NET API Reference
description: Implements the IWarningCallbackaspose.words/iwarningcallback interface. Adds a warning to this collection.
type: docs
weight: 60
url: /net/aspose.words/warninginfocollection/warning/
---
## WarningInfoCollection.Warning method

Implements the [`IWarningCallback`](../../iwarningcallback) interface. Adds a warning to this collection.

```csharp
public void Warning(WarningInfo info)
```

## Examples

Shows how to set the property for finding the closest match for a missing font from the available font sources.

```csharp
[Test]
public void EnableFontSubstitution()
{
    // Open a document that contains text formatted with a font that does not exist in any of our font sources.
    Document doc = new Document(MyDir + "Missing font.docx");

    // Assign a callback for handling font substitution warnings.
    HandleDocumentSubstitutionWarnings substitutionWarningHandler = new HandleDocumentSubstitutionWarnings();
    doc.WarningCallback = substitutionWarningHandler;

    // Set a default font name and enable font substitution.
    FontSettings fontSettings = new FontSettings();
    fontSettings.SubstitutionSettings.DefaultFontSubstitution.DefaultFontName = "Arial";
    ;
    fontSettings.SubstitutionSettings.FontInfoSubstitution.Enabled = true;

    // We will get a font substitution warning if we save a document with a missing font.
    doc.FontSettings = fontSettings;
    doc.Save(ArtifactsDir + "FontSettings.EnableFontSubstitution.pdf");

    using (IEnumerator<WarningInfo> warnings = substitutionWarningHandler.FontWarnings.GetEnumerator())
        while (warnings.MoveNext())
            Console.WriteLine(warnings.Current.Description);

    // We can also verify warnings in the collection and clear them.
    Assert.AreEqual(WarningSource.Layout, substitutionWarningHandler.FontWarnings[0].Source);
    Assert.AreEqual(
        "Font '28 Days Later' has not been found. Using 'Calibri' font instead. Reason: alternative name from document.",
        substitutionWarningHandler.FontWarnings[0].Description);

    substitutionWarningHandler.FontWarnings.Clear();

    Assert.That(substitutionWarningHandler.FontWarnings, Is.Empty);
}

public class HandleDocumentSubstitutionWarnings : IWarningCallback
{
    /// <summary>
    /// Called every time a warning occurs during loading/saving.
    /// </summary>
    public void Warning(WarningInfo info)
    {
        if (info.WarningType == WarningType.FontSubstitution)
            FontWarnings.Warning(info);
    }

    public WarningInfoCollection FontWarnings = new WarningInfoCollection();
}
```

### See Also

* class [WarningInfo](../../warninginfo)
* class [WarningInfoCollection](../../warninginfocollection)
* namespace [Aspose.Words](../../warninginfocollection)
* assembly [Aspose.Words](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Words.dll -->
