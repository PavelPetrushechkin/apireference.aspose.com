﻿---
title: BookmarkStart class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents a start of a bookmark in a Word document."
type: docs
weight: 60
url: /python-net/aspose.words/bookmarkstart/
---

## BookmarkStart class

Represents a start of a bookmark in a Word document.


A complete bookmark in a Word document consists of a [BookmarkStart](./)
and a matching [BookmarkEnd](../bookmarkend/) with the same bookmark name.

[BookmarkStart](./) and [BookmarkEnd](../bookmarkend/) are just markers inside a document
that specify where the bookmark starts and ends.

Use the [BookmarkStart.bookmark](./bookmark/) class as a "facade" to work with a bookmark
as a single object.




**Inheritance:** [BookmarkStart](./) → [Node](../node/)

### Constructors
| Name | Description |
| --- | --- |
| [BookmarkStart(doc, name)](./__init__/#documentbase_str) | Initializes a new instance of the [BookmarkStart](./) class. |

### Properties

| Name | Description |
| --- | --- |
| [bookmark](./bookmark/) | Gets the facade object that encapsulates this bookmark start and end. |
| [custom_node_id](../node/custom_node_id/) | Specifies custom node identifier.<br>(Inherited from [Node](../node/)) |
| [document](../node/document/) | Gets the document to which this node belongs.<br>(Inherited from [Node](../node/)) |
| [is_composite](../node/is_composite/) | Returns true if this node can contain other nodes.<br>(Inherited from [Node](../node/)) |
| [name](./name/) | Gets or sets the bookmark name. |
| [next_sibling](../node/next_sibling/) | Gets the node immediately following this node.<br>(Inherited from [Node](../node/)) |
| [node_type](./node_type/) | Returns [NodeType.BOOKMARK_START](../nodetype/#BOOKMARK_START). |
| [parent_node](../node/parent_node/) | Gets the immediate parent of this node.<br>(Inherited from [Node](../node/)) |
| [previous_sibling](../node/previous_sibling/) | Gets the node immediately preceding this node.<br>(Inherited from [Node](../node/)) |
| [range](../node/range/) | Returns a **Range** object that represents the portion of a document that is contained in this node.<br>(Inherited from [Node](../node/)) |

### Methods

| Name | Description |
| --- | --- |
|[ accept(visitor)](./accept/#documentvisitor) | Accepts a visitor. |
|[ clone(is_clone_children)](../node/clone/#bool) | Creates a duplicate of the node.<br>(Inherited from [Node](../node/)) |
|[ get_ancestor(ancestor_type)](../node/get_ancestor/#nodetype) | Gets the first ancestor of the specified [NodeType](../nodetype/).<br>(Inherited from [Node](../node/)) |
|[ get_text()](./get_text/#default) | Returns an empty string. |
|[ next_pre_order(root_node)](../node/next_pre_order/#node) | Gets next node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../node/)) |
|[ node_type_to_string(node_type)](../node/node_type_to_string/#nodetype) | A utility method that converts a node type enum value into a user friendly string.<br>(Inherited from [Node](../node/)) |
|[ previous_pre_order(root_node)](../node/previous_pre_order/#node) | Gets the previous node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../node/)) |
|[ remove()](../node/remove/#default) | Removes itself from the parent.<br>(Inherited from [Node](../node/)) |
|[ to_string(save_format)](../node/to_string/#saveformat) | Exports the content of the node into a string in the specified format.<br>(Inherited from [Node](../node/)) |
|[ to_string(save_options)](../node/to_string/#saveoptions) | Exports the content of the node into a string using the specified save options.<br>(Inherited from [Node](../node/)) |

### See Also

* module [aspose.words](../)
* class [Node](../node/)

