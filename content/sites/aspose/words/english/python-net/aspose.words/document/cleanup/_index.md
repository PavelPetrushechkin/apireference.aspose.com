﻿---
title: cleanup method
second_title: Aspose.Words for Python via .NET API Reference
description: "aspose.words.Document.cleanup method"
type: docs
weight: 520
url: /python-net/aspose.words/document/cleanup/
---

## cleanup() {#default}

Cleans unused styles and lists from the document.


```python
def cleanup(self):
    ...
```

## cleanup(options) {#cleanupoptions}

Cleans unused styles and lists from the document depending on given [CleanupOptions](../../cleanupoptions/).



```python
def cleanup(self, options: aspose.words.CleanupOptions):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | [CleanupOptions](../../cleanupoptions/) |  |

## Examples

Shows how to remove unused custom styles from a document.

```python
doc = aw.Document()

doc.styles.add(aw.StyleType.LIST, "MyListStyle1")
doc.styles.add(aw.StyleType.LIST, "MyListStyle2")
doc.styles.add(aw.StyleType.CHARACTER, "MyParagraphStyle1")
doc.styles.add(aw.StyleType.CHARACTER, "MyParagraphStyle2")

# Combined with the built-in styles, the document now has eight styles.
# A custom style counts as "used" while applied to some part of the document,
# which means that the four styles we added are currently unused.
self.assertEqual(8, doc.styles.count)

# Apply a custom character style, and then a custom list style. Doing so will mark the styles as "used".
builder = aw.DocumentBuilder(doc)
builder.font.style = doc.styles.get_by_name("MyParagraphStyle1")
builder.writeln("Hello world!")

builder.list_format.list = doc.lists.add(doc.styles.get_by_name("MyListStyle1"))
builder.writeln("Item 1")
builder.writeln("Item 2")

doc.cleanup()

self.assertEqual(6, doc.styles.count)

# Removing every node that a custom style is applied to marks it as "unused" again.
# Run the "cleanup" method again to remove them.
doc.first_section.body.remove_all_children()
doc.cleanup()

self.assertEqual(4, doc.styles.count)
```

Shows how to remove all unused custom styles from a document.

```python
doc = aw.Document()

doc.styles.add(aw.StyleType.LIST, "MyListStyle1")
doc.styles.add(aw.StyleType.LIST, "MyListStyle2")
doc.styles.add(aw.StyleType.CHARACTER, "MyParagraphStyle1")
doc.styles.add(aw.StyleType.CHARACTER, "MyParagraphStyle2")

# Combined with the built-in styles, the document now has eight styles.
# A custom style is marked as "used" while there is any text within the document
# formatted in that style. This means that the 4 styles we added are currently unused.
self.assertEqual(8, doc.styles.count)

# Apply a custom character style, and then a custom list style. Doing so will mark them as "used".
builder = aw.DocumentBuilder(doc)
builder.font.style = doc.styles.get_by_name("MyParagraphStyle1")
builder.writeln("Hello world!")

builder.list_format.list = doc.lists.add(doc.styles.get_by_name("MyListStyle1"))
builder.writeln("Item 1")
builder.writeln("Item 2")

# Now, there is one unused character style and one unused list style.
# The "cleanup" method, when configured with a CleanupOptions object, can target unused styles and remove them.
cleanup_options = aw.CleanupOptions()
cleanup_options.unused_lists = True
cleanup_options.unused_styles = True
cleanup_options.unused_builtin_styles = True

doc.cleanup(cleanup_options)

self.assertEqual(4, doc.styles.count)

# Removing every node that a custom style is applied to marks it as "unused" again.
# Rerun the "cleanup" method to remove them.
doc.first_section.body.remove_all_children()
doc.cleanup(cleanup_options)

self.assertEqual(2, doc.styles.count)
```

## See Also

* module [aspose.words](../../)
* class [Document](../)

