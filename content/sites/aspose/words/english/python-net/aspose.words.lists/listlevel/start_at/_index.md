﻿---
title: start_at property
second_title: Aspose.Words for Python via .NET API Reference
description: "Returns or sets the starting number for this list level."
type: docs
weight: 110
url: /python-net/aspose.words.lists/listlevel/start_at/
---

## ListLevel.start_at property

Returns or sets the starting number for this list level.

Default value is 1.




### Examples

Shows how to apply custom list formatting to paragraphs when using DocumentBuilder.

```python
doc = aw.Document()

# A list allows us to organize and decorate sets of paragraphs with prefix symbols and indents.
# We can create nested lists by increasing the indent level.
# We can begin and end a list by using a document builder's "list_format" property.
# Each paragraph that we add between a list's start and the end will become an item in the list.
# Create a list from a Microsoft Word template, and customize the first two of its list levels.
list = doc.lists.add(aw.lists.ListTemplate.NUMBER_DEFAULT)

list_level = list.list_levels[0]
list_level.font.color = drawing.Color.red
list_level.font.size = 24
list_level.number_style = aw.NumberStyle.ORDINAL_TEXT
list_level.start_at = 21
list_level.number_format = "\u0000"

list_level.number_position = -36
list_level.text_position = 144
list_level.tab_position = 144

list_level = list.list_levels[1]
list_level.alignment = aw.lists.ListLevelAlignment.RIGHT
list_level.number_style = aw.NumberStyle.BULLET
list_level.font.name = "Wingdings"
list_level.font.color = drawing.Color.blue
list_level.font.size = 24

# This NumberFormat value will create star-shaped bullet list symbols.
list_level.number_format = "\uf0af"
list_level.trailing_character = aw.lists.ListTrailingCharacter.SPACE
list_level.number_position = 144

# Create paragraphs and apply both list levels of our custom list formatting to them.
builder = aw.DocumentBuilder(doc)

builder.list_format.list = list
builder.writeln("The quick brown fox...")
builder.writeln("The quick brown fox...")

builder.list_format.list_indent()
builder.writeln("jumped over the lazy dog.")
builder.writeln("jumped over the lazy dog.")

builder.list_format.list_outdent()
builder.writeln("The quick brown fox...")

builder.list_format.remove_numbers()

builder.document.save(ARTIFACTS_DIR + "Lists.create_custom_list.docx")
```

Shows how to restart numbering in a list by copying a list.

```python
doc = aw.Document()

# A list allows us to organize and decorate sets of paragraphs with prefix symbols and indents.
# We can create nested lists by increasing the indent level.
# We can begin and end a list by using a document builder's "list_format" property.
# Each paragraph that we add between a list's start and the end will become an item in the list.
# Create a list from a Microsoft Word template, and customize its first list level.
list1 = doc.lists.add(aw.lists.ListTemplate.NUMBER_ARABIC_PARENTHESIS)
list1.list_levels[0].font.color = drawing.Color.red
list1.list_levels[0].alignment = aw.lists.ListLevelAlignment.RIGHT

# Apply our list to some paragraphs.
builder = aw.DocumentBuilder(doc)

builder.writeln("List 1 starts below:")
builder.list_format.list = list1
builder.writeln("Item 1")
builder.writeln("Item 2")
builder.list_format.remove_numbers()

# We can add a copy of an existing list to the document's list collection
# to create a similar list without making changes to the original.
list2 = doc.lists.add_copy(list1)
list2.list_levels[0].font.color = drawing.Color.blue
list2.list_levels[0].start_at = 10

# Apply the second list to new paragraphs.
builder.writeln("List 2 starts below:")
builder.list_format.list = list2
builder.writeln("Item 1")
builder.writeln("Item 2")
builder.list_format.remove_numbers()

doc.save(ARTIFACTS_DIR + "Lists.restart_numbering_using_list_copy.docx")
```

### See Also

* module [aspose.words.lists](../../)
* class [ListLevel](../)

