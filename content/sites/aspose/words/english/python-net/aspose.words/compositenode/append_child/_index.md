﻿---
title: append_child method
second_title: Aspose.Words for Python via .NET API Reference
description: "Adds the specified node to the end of the list of child nodes for this node."
type: docs
weight: 70
url: /python-net/aspose.words/compositenode/append_child/
---

## append_child(new_child) {#node}

Adds the specified node to the end of the list of child nodes for this node.


```python
def append_child(self, new_child: aspose.words.Node):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| new_child | [Node](../../node/) |  |

If the newChild is already in the tree, it is first removed.

If the node being inserted was created from another document, you should use 
[DocumentBase.import_node()](../../documentbase/import_node/#node_bool_importformatmode) to import the node to the current document. 
The imported node can then be inserted into the current document.




### Returns

The node added.


### Examples

Shows how to construct an Aspose.Words document by hand.

```python
doc = aw.Document()

# A blank document contains one section, one body and one paragraph.
# Call the "remove_all_children" method to remove all those nodes,
# and end up with a document node with no children.
doc.remove_all_children()

# This document now has no composite child nodes that we can add content to.
# If we wish to edit it, we will need to repopulate its node collection.
# First, create a new section, and then append it as a child to the root document node.
section = aw.Section(doc)
doc.append_child(section)

# Set some page setup properties for the section.
section.page_setup.section_start = aw.SectionStart.NEW_PAGE
section.page_setup.paper_size = aw.PaperSize.LETTER

# A section needs a body, which will contain and display all its contents
# on the page between the section's header and footer.
body = aw.Body(doc)
section.append_child(body)

# Create a paragraph, set some formatting properties, and then append it as a child to the body.
para = aw.Paragraph(doc)

para.paragraph_format.style_name = "Heading 1"
para.paragraph_format.alignment = aw.ParagraphAlignment.CENTER

body.append_child(para)

# Finally, add some content to do the document. Create a run,
# set its appearance and contents, and then append it as a child to the paragraph.
run = aw.Run(doc)
run.text = "Hello World!"
run.font.color = drawing.Color.red
para.append_child(run)

self.assertEqual("Hello World!", doc.get_text().strip())

doc.save(ARTIFACTS_DIR + "Section.create_manually.docx")
```

### See Also

* module [aspose.words](../../)
* class [CompositeNode](../)

