﻿---
title: EditableRangeEnd class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents an end of an editable range in a Word document."
type: docs
weight: 340
url: /python-net/aspose.words/editablerangeend/
---

## EditableRangeEnd class

Represents an end of an editable range in a Word document.


A complete editable range  in a Word document consists of a [EditableRangeEnd.editable_range_start](./editable_range_start/)
and a matching [EditableRangeEnd](./) with the same Id.

[EditableRangeEnd.editable_range_start](./editable_range_start/) and [EditableRangeEnd](./) are just markers inside a document
that specify where the editable range starts and ends.

Use the [EditableRange](../editablerange/) class as a "facade" to work with an editable range 
as a single object.

> **NOTE**
>
> Currently editable ranges are supported only at the inline-level, that is inside [Paragraph](../paragraph/),
> but editable range start and editable range end can be in different paragraphs.




**Inheritance:** [EditableRangeEnd](./) → [Node](../node/)

### Properties

| Name | Description |
| --- | --- |
| [custom_node_id](../node/custom_node_id/) | Specifies custom node identifier.<br>(Inherited from [Node](../node/)) |
| [document](../node/document/) | Gets the document to which this node belongs.<br>(Inherited from [Node](../node/)) |
| [editable_range_start](./editable_range_start/) | Corresponding EditableRangeStart, received by ID. |
| [id](./id/) | Specifies the identifier of the editable range. |
| [is_composite](../node/is_composite/) | Returns true if this node can contain other nodes.<br>(Inherited from [Node](../node/)) |
| [next_sibling](../node/next_sibling/) | Gets the node immediately following this node.<br>(Inherited from [Node](../node/)) |
| [node_type](./node_type/) | Returns [NodeType.EDITABLE_RANGE_END](../nodetype/#EDITABLE_RANGE_END). |
| [parent_node](../node/parent_node/) | Gets the immediate parent of this node.<br>(Inherited from [Node](../node/)) |
| [previous_sibling](../node/previous_sibling/) | Gets the node immediately preceding this node.<br>(Inherited from [Node](../node/)) |
| [range](../node/range/) | Returns a **Range** object that represents the portion of a document that is contained in this node.<br>(Inherited from [Node](../node/)) |

### Methods

| Name | Description |
| --- | --- |
|[ accept(visitor)](./accept/#documentvisitor) | Accepts a visitor. |
|[ clone(is_clone_children)](../node/clone/#bool) | Creates a duplicate of the node.<br>(Inherited from [Node](../node/)) |
|[ get_ancestor(ancestor_type)](../node/get_ancestor/#nodetype) | Gets the first ancestor of the specified [NodeType](../nodetype/).<br>(Inherited from [Node](../node/)) |
|[ get_text()](../node/get_text/#default) | Gets the text of this node and of all its children.<br>(Inherited from [Node](../node/)) |
|[ next_pre_order(root_node)](../node/next_pre_order/#node) | Gets next node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../node/)) |
|[ node_type_to_string(node_type)](../node/node_type_to_string/#nodetype) | A utility method that converts a node type enum value into a user friendly string.<br>(Inherited from [Node](../node/)) |
|[ previous_pre_order(root_node)](../node/previous_pre_order/#node) | Gets the previous node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../node/)) |
|[ remove()](../node/remove/#default) | Removes itself from the parent.<br>(Inherited from [Node](../node/)) |
|[ to_string(save_format)](../node/to_string/#saveformat) | Exports the content of the node into a string in the specified format.<br>(Inherited from [Node](../node/)) |
|[ to_string(save_options)](../node/to_string/#saveoptions) | Exports the content of the node into a string using the specified save options.<br>(Inherited from [Node](../node/)) |

### See Also

* module [aspose.words](../)
* class [Node](../node/)

