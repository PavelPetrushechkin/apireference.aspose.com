﻿---
title: GroupShape class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents a group of shapes in a document."
type: docs
weight: 130
url: /python-net/aspose.words.drawing/groupshape/
---

## GroupShape class

Represents a group of shapes in a document.


A [GroupShape](./) is a composite node and can have [Shape](../shape/) and
[GroupShape](./) nodes as children.

Each [GroupShape](./) defines a new coordinate system for its child shapes.
The coordinate system is defined using the [ShapeBase.coord_size](../shapebase/coord_size/) and 
[ShapeBase.coord_origin](../shapebase/coord_origin/) properties.




**Inheritance:** [GroupShape](./) → [ShapeBase](../shapebase/) → [CompositeNode](../../aspose.words/compositenode/) → [Node](../../aspose.words/node/)

### Constructors
| Name | Description |
| --- | --- |
| [GroupShape(doc)](./__init__/#documentbase) | Creates a new group shape. |

### Properties

| Name | Description |
| --- | --- |
| [allow_overlap](../shapebase/allow_overlap/) | Gets or sets a value that specifies whether this shape can overlap other shapes.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [alternative_text](../shapebase/alternative_text/) | Defines alternative text to be displayed instead of a graphic.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [anchor_locked](../shapebase/anchor_locked/) | Specifies whether the shape's anchor is locked.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [aspect_ratio_locked](../shapebase/aspect_ratio_locked/) | Specifies whether the shape's aspect ratio is locked.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [behind_text](../shapebase/behind_text/) | Specifies whether the shape is below or above text.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [bottom](../shapebase/bottom/) | Gets the position of the bottom edge of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [bounds](../shapebase/bounds/) | Gets or sets the location and size of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [bounds_in_points](../shapebase/bounds_in_points/) | Gets the location and size of the containing block of the shape in points, relative to the anchor of the topmost shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [bounds_with_effects](../shapebase/bounds_with_effects/) | Gets final extent that this shape object has after applying drawing effects. Value is measured in points.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [can_have_image](../shapebase/can_have_image/) | Returns true if the shape type allows the shape to have an image.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [child_nodes](../../aspose.words/compositenode/child_nodes/) | Gets all immediate child nodes of this node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
| [coord_origin](../shapebase/coord_origin/) | The coordinates at the top-left corner of the containing block of this shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [coord_size](../shapebase/coord_size/) | The width and height of the coordinate space inside the containing block of this shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [count](../../aspose.words/compositenode/count/) | Gets the number of immediate children of this node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
| [custom_node_id](../../aspose.words/node/custom_node_id/) | Specifies custom node identifier.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [distance_bottom](../shapebase/distance_bottom/) | Returns or sets the distance (in points) between the document text and the bottom edge of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [distance_left](../shapebase/distance_left/) | Returns or sets the distance (in points) between the document text and the left edge of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [distance_right](../shapebase/distance_right/) | Returns or sets the distance (in points) between the document text and the right edge of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [distance_top](../shapebase/distance_top/) | Returns or sets the distance (in points) between the document text and the top edge of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [document](../../aspose.words/node/document/) | Gets the document to which this node belongs.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [fill](../shapebase/fill/) | Gets fill formatting for the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [first_child](../../aspose.words/compositenode/first_child/) | Gets the first child of the node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
| [flip_orientation](../shapebase/flip_orientation/) | Switches the orientation of a shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [font](../shapebase/font/) | Provides access to the font formatting of this object.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [has_child_nodes](../../aspose.words/compositenode/has_child_nodes/) | Returns true if this node has any child nodes.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
| [height](../shapebase/height/) | Gets or sets the height of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [horizontal_alignment](../shapebase/horizontal_alignment/) | Specifies how the shape is positioned horizontally.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [href](../shapebase/href/) | Gets or sets the full hyperlink address for a shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_composite](../../aspose.words/node/is_composite/) | Returns true if this node can contain other nodes.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [is_decorative](../shapebase/is_decorative/) | Gets or sets the flag that specifies whether the shape is decorative in the document.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_delete_revision](../shapebase/is_delete_revision/) | Returns true if this object was deleted in Microsoft Word while change tracking was enabled.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_group](../shapebase/is_group/) | Returns true if this is a group shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_horizontal_rule](../shapebase/is_horizontal_rule/) | Returns true if this shape is a horizontal rule.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_image](../shapebase/is_image/) | Returns true if this shape is an image shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_inline](../shapebase/is_inline/) | A quick way to determine if this shape is positioned inline with text.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_insert_revision](../shapebase/is_insert_revision/) | Returns true if this object was inserted in Microsoft Word while change tracking was enabled.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_layout_in_cell](../shapebase/is_layout_in_cell/) | Gets or sets a flag indicating whether the shape is displayed inside a table or outside of it.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_move_from_revision](../shapebase/is_move_from_revision/) | Returns **true** if this object was moved (deleted) in Microsoft Word while change tracking was enabled.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_move_to_revision](../shapebase/is_move_to_revision/) | Returns **true** if this object was moved (inserted) in Microsoft Word while change tracking was enabled.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_signature_line](../shapebase/is_signature_line/) | Indicates that shape is a SignatureLine.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_top_level](../shapebase/is_top_level/) | Returns true if this shape is not a child of a group shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [is_word_art](../shapebase/is_word_art/) | Returns true if this shape is a WordArt object.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [last_child](../../aspose.words/compositenode/last_child/) | Gets the last child of the node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
| [left](../shapebase/left/) | Gets or sets the position of the left edge of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [markup_language](../shapebase/markup_language/) | Gets MarkupLanguage used for this graphic object.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [name](../shapebase/name/) | Gets or sets the optional shape name.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [next_sibling](../../aspose.words/node/next_sibling/) | Gets the node immediately following this node.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [node_type](./node_type/) | Returns [NodeType.GROUP_SHAPE](../../aspose.words/nodetype/#GROUP_SHAPE). |
| [parent_node](../../aspose.words/node/parent_node/) | Gets the immediate parent of this node.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [parent_paragraph](../shapebase/parent_paragraph/) | Returns the immediate parent paragraph.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [previous_sibling](../../aspose.words/node/previous_sibling/) | Gets the node immediately preceding this node.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [range](../../aspose.words/node/range/) | Returns a **Range** object that represents the portion of a document that is contained in this node.<br>(Inherited from [Node](../../aspose.words/node/)) |
| [relative_horizontal_position](../shapebase/relative_horizontal_position/) | Specifies relative to what the shape is positioned horizontally.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [relative_vertical_position](../shapebase/relative_vertical_position/) | Specifies relative to what the shape is positioned vertically.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [right](../shapebase/right/) | Gets the position of the right edge of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [rotation](../shapebase/rotation/) | Defines the angle (in degrees) that a shape is rotated. Positive value corresponds to clockwise rotation angle.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [screen_tip](../shapebase/screen_tip/) | Defines the text displayed when the mouse pointer moves over the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [shadow_format](../shapebase/shadow_format/) | Gets shadow formatting for the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [shape_type](../shapebase/shape_type/) | Gets the shape type.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [size_in_points](../shapebase/size_in_points/) | Gets the size of the shape in points.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [target](../shapebase/target/) | Gets or sets the target frame for the shape hyperlink.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [title](../shapebase/title/) | Gets or sets the title (caption) of the current shape object.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [top](../shapebase/top/) | Gets or sets the position of the top edge of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [vertical_alignment](../shapebase/vertical_alignment/) | Specifies how the shape is positioned vertically.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [width](../shapebase/width/) | Gets or sets the width of the containing block of the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [wrap_side](../shapebase/wrap_side/) | Specifies how the text is wrapped around the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [wrap_type](../shapebase/wrap_type/) | Defines whether the shape is inline or floating. For floating shapes defines the wrapping mode for text around the shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
| [z_order](../shapebase/z_order/) | Determines the display order of overlapping shapes.<br>(Inherited from [ShapeBase](../shapebase/)) |

### Methods

| Name | Description |
| --- | --- |
|[ accept(visitor)](./accept/#documentvisitor) | Accepts a visitor. |
|[ adjust_with_effects(source)](../shapebase/adjust_with_effects/#rectanglef) | Adds to the source rectangle values of the effect extent and returns the final rectangle.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ append_child(new_child)](../../aspose.words/compositenode/append_child/#node) | Adds the specified node to the end of the list of child nodes for this node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ clone(is_clone_children)](../../aspose.words/node/clone/#bool) | Creates a duplicate of the node.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ fetch_inherited_shape_attr(key)](../shapebase/fetch_inherited_shape_attr/#int) | Reserved for system use. IShapeAttrSource.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ fetch_shape_attr(key)](../shapebase/fetch_shape_attr/#int) | Reserved for system use. IShapeAttrSource.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ get_ancestor(ancestor_type)](../../aspose.words/node/get_ancestor/#nodetype) | Gets the first ancestor of the specified [NodeType](../../aspose.words/nodetype/).<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ get_child(node_type, index, is_deep)](../../aspose.words/compositenode/get_child/#nodetype_int_bool) | Returns an Nth child node that matches the specified type.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ get_child_nodes(node_type, is_deep)](../../aspose.words/compositenode/get_child_nodes/#nodetype_bool) | Returns a live collection of child nodes that match the specified type.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ get_direct_shape_attr(key)](../shapebase/get_direct_shape_attr/#int) | Reserved for system use. IShapeAttrSource.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ get_shape_renderer()](../shapebase/get_shape_renderer/#default) | Creates and returns an object that can be used to render this shape into an image.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ get_text()](../../aspose.words/node/get_text/#default) | Gets the text of this node and of all its children.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ index_of(child)](../../aspose.words/compositenode/index_of/#node) | Returns the index of the specified child node in the child node array.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ insert_after(new_child, ref_child)](../../aspose.words/compositenode/insert_after/#node_node) | Inserts the specified node immediately after the specified reference node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ insert_before(new_child, ref_child)](../../aspose.words/compositenode/insert_before/#node_node) | Inserts the specified node immediately before the specified reference node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ local_to_parent(value)](../shapebase/local_to_parent/#pointf) | Converts a value from the local coordinate space into the coordinate space of the parent shape.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ next_pre_order(root_node)](../../aspose.words/node/next_pre_order/#node) | Gets next node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ node_type_to_string(node_type)](../../aspose.words/node/node_type_to_string/#nodetype) | A utility method that converts a node type enum value into a user friendly string.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ prepend_child(new_child)](../../aspose.words/compositenode/prepend_child/#node) | Adds the specified node to the beginning of the list of child nodes for this node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ previous_pre_order(root_node)](../../aspose.words/node/previous_pre_order/#node) | Gets the previous node according to the pre-order tree traversal algorithm.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ remove()](../../aspose.words/node/remove/#default) | Removes itself from the parent.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ remove_all_children()](../../aspose.words/compositenode/remove_all_children/#default) | Removes all the child nodes of the current node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ remove_child(old_child)](../../aspose.words/compositenode/remove_child/#node) | Removes the specified child node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ remove_shape_attr(key)](../shapebase/remove_shape_attr/#int) | Reserved for system use. IShapeAttrSource.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ remove_smart_tags()](../../aspose.words/compositenode/remove_smart_tags/#default) | Removes all [SmartTag](../../aspose.words.markup/smarttag/) descendant nodes of the current node.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ select_nodes(xpath)](../../aspose.words/compositenode/select_nodes/#str) | Selects a list of nodes matching the XPath expression.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ select_single_node(xpath)](../../aspose.words/compositenode/select_single_node/#str) | Selects the first Node that matches the XPath expression.<br>(Inherited from [CompositeNode](../../aspose.words/compositenode/)) |
|[ set_shape_attr(key, value)](../shapebase/set_shape_attr/#int_object) | Reserved for system use. IShapeAttrSource.<br>(Inherited from [ShapeBase](../shapebase/)) |
|[ to_string(save_format)](../../aspose.words/node/to_string/#saveformat) | Exports the content of the node into a string in the specified format.<br>(Inherited from [Node](../../aspose.words/node/)) |
|[ to_string(save_options)](../../aspose.words/node/to_string/#saveoptions) | Exports the content of the node into a string using the specified save options.<br>(Inherited from [Node](../../aspose.words/node/)) |

### See Also

* module [aspose.words.drawing](../)
* class [ShapeBase](../shapebase/)
* class [Shape](../shape/)

