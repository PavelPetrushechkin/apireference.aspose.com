﻿---
title: HeaderFooterCollection indexer
second_title: Aspose.Words for Python via .NET API Reference
description: "Retrieves a HeaderFooter at the given index."
type: docs
weight: 10
url: /python-net/aspose.words/headerfootercollection/__getitem__/
---

## \_\_getitem\_\_(index) {#int}

Retrieves a **HeaderFooter** at the given index.



```python
def __getitem__(self, index: int):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

The index is zero-based.

Negative indexes are allowed and indicate access from the back of the collection. 
For example -1 means the last item, -2 means the second before last and so on.

If index is greater than or equal to the number of items in the list, this returns a null reference.

If index is negative and its absolute value is greater than the number of items in the list, this returns a null reference.




### Examples

Shows how to link headers and footers between sections.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

builder.write("Section 1")
builder.insert_break(aw.BreakType.SECTION_BREAK_NEW_PAGE)
builder.write("Section 2")
builder.insert_break(aw.BreakType.SECTION_BREAK_NEW_PAGE)
builder.write("Section 3")

# Move to the first section and create a header and a footer. By default,
# the header and the footer will only appear on pages in the section that contains them.
builder.move_to_section(0)

builder.move_to_header_footer(aw.HeaderFooterType.HEADER_PRIMARY)
builder.write("This is the header, which will be displayed in sections 1 and 2.")

builder.move_to_header_footer(aw.HeaderFooterType.FOOTER_PRIMARY)
builder.write("This is the footer, which will be displayed in sections 1, 2 and 3.")

# We can link a section's headers/footers to the previous section's headers/footers
# to allow the linking section to display the linked section's headers/footers.
doc.sections[1].headers_footers.link_to_previous(True)

# Each section will still have its own header/footer objects. When we link sections,
# the linking section will display the linked section's header/footers while keeping its own.
self.assertNotEqual(doc.sections[0].headers_footers[0], doc.sections[1].headers_footers[0])
self.assertNotEqual(doc.sections[0].headers_footers[0].parent_section, doc.sections[1].headers_footers[0].parent_section)

# Link the headers/footers of the third section to the headers/footers of the second section.
# The second section already links to the first section's header/footers,
# so linking to the second section will create a link chain.
# The first, second, and now the third sections will all display the first section's headers.
doc.sections[2].headers_footers.link_to_previous(True)

# We can un-link a previous section's header/footers by passing "False" when calling the LinkToPrevious method.
doc.sections[2].headers_footers.link_to_previous(False)

# We can also select only a specific type of header/footer to link using this method.
# The third section now will have the same footer as the second and first sections, but not the header.
doc.sections[2].headers_footers.link_to_previous(aw.HeaderFooterType.FOOTER_PRIMARY, True)

# The first section's header/footers cannot link themselves to anything because there is no previous section.
self.assertEqual(2, doc.sections[0].headers_footers.count)
self.assertEqual(2, len([node for node in doc.sections[0].headers_footers if not node.as_header_footer().is_linked_to_previous]))

# All the second section's header/footers are linked to the first section's headers/footers.
self.assertEqual(6, doc.sections[1].headers_footers.count)
self.assertEqual(6, len([node for node in doc.sections[1].headers_footers if node.as_header_footer().is_linked_to_previous]))

# In the third section, only the footer is linked to the first section's footer via the second section.
self.assertEqual(6, doc.sections[2].headers_footers.count)
self.assertEqual(5, len([node for node in doc.sections[2].headers_footers if not node.as_header_footer().is_linked_to_previous]))
self.assertTrue(doc.sections[2].headers_footers[3].is_linked_to_previous)

doc.save(ARTIFACTS_DIR + "HeaderFooter.link.docx")
```

### See Also

* module [aspose.words](../../)
* class [HeaderFooterCollection](../)

