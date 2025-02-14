﻿---
title: visit_editable_range_start method
second_title: Aspose.Words for Python via .NET API Reference
description: "Called when a start of an editable range is encountered in the document."
type: docs
weight: 170
url: /python-net/aspose.words/documentvisitor/visit_editable_range_start/
---

## visit_editable_range_start(editable_range_start) {#editablerangestart}

Called when a start of an editable range is encountered in the document.


```python
def visit_editable_range_start(self, editable_range_start: aspose.words.EditableRangeStart):
    ...
```

| Parameter | Type | Description |
| --- | --- | --- |
| editable_range_start | [EditableRangeStart](../../editablerangestart/) |  |

### Returns

A [VisitorAction](../../visitoraction/) value that specifies how to continue the enumeration.


### Examples

Shows how to print the node structure of every editable range in a document.

```python
def test_editable_range_to_text(self):

    doc = aw.Document(MY_DIR + "DocumentVisitor-compatible features.docx")
    visitor = ExDocumentVisitor.EditableRangeStructurePrinter()

    # When we get a composite node to accept a document visitor, the visitor visits the accepting node,
    # and then traverses all the node's children in a depth-first manner.
    # The visitor can read and modify each visited node.
    doc.accept(visitor)

    print(visitor.get_text())

class EditableRangeStructurePrinter(aw.DocumentVisitor):
    """Traverses a node's non-binary tree of child nodes.
    Creates a map in the form of a string of all encountered EditableRange nodes and their children."""

    def __init__(self):

        aw.DocumentVisitor.__init__(self)

        self.builder = io.StringIO()
        self.visitor_is_inside_editable_range = False
        self.doc_traversal_depth = 0

    def get_text(self) -> str:
        """Gets the plain text of the document that was accumulated by the visitor."""

        return self.builder.getvalue()

    def visit_run(self, run: aw.Run) -> aw.VisitorAction:
        """Called when a Run node is encountered in the document."""

        # We want to print the contents of runs, but only if they are inside shapes, as they would be in the case of text boxes
        if self.visitor_is_inside_editable_range:
            self._indent_and_append_line("[Run] \"" + run.get_text() + "\"")

        return aw.VisitorAction.CONTINUE

    def visit_editable_range_start(self, editable_range_start: aw.EditableRangeStart) -> aw.VisitorAction:
        """Called when an EditableRange node is encountered in the document."""

        self._indent_and_append_line("[EditableRange start] ID: " + editable_range_start.id + " Owner: " +
                            editable_range_start.editable_range.single_user)
        self.doc_traversal_depth += 1
        self.visitor_is_inside_editable_range = True

        return aw.VisitorAction.CONTINUE

    def visit_editable_range_end(self, editable_range_end: aw.EditableRangeEnd) -> aw.VisitorAction:
        """Called when the visiting of a EditableRange node is ended."""

        self.doc_traversal_depth -= 1
        self._indent_and_append_line("[EditableRange end]")
        self.visitor_is_inside_editable_range = False

        return aw.VisitorAction.CONTINUE

    def _indent_and_append_line(self, text: str):
        """Append a line to the output and indent it depending on how deep the visitor is into the document tree."""

        for i in range(self.doc_traversal_depth):
            self.builder.write("|  ")

        self.builder.write(text + "\n")
```

### See Also

* module [aspose.words](../../)
* class [DocumentVisitor](../)

